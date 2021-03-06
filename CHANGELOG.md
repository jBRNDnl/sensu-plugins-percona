# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]
### [1.1.0] - 2017-08-09
### Removed
- removed `mysql` gem dep as we have `mysql2` and `mysql` does not work on ruby 2.4 and has been abandoned. (@majormoses)

### Changed
- check-percona-cluster-size.rb: converted to use `mysql2` gem (@majormoses)
- check-wsrep-ready.rb: converted to use `mysql2` gem (@majormoses)

### Added
- ruby 2.4 testing to travis (@majormoses)
- slack badge (@majormoses)

## [1.0.0] - 2016-09-25
### Added
- Ruby 2.3.0 support
- Add `check-wsrep-ready` to check the ready status of a cluster (@aberrios85)

### Removed
- Ruby 1.9.3 support

### Changed
- Update to rubocop 0.40 and cleanup

## [0.0.2] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## 0.0.1 - 2015-06-11
### Added
- initial release
- added ability to use ini files

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-percona/compare/1.1.0...HEAD
[1.1.0]: https://github.com/sensu-plugins/sensu-plugins-percona/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-percona/compare/0.0.2...1.0.0
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-percona/compare/0.0.1...0.0.2
