# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v0.5.0] - 2020-11-01

### Added

- you can now use a permanent access token instead of your username and password to autenticate with the Ackee API

### Changed

- include data of last 30 days instead of last 7 days
- better error handling
- refactor config validation

## [v0.4.1] - 2020-10-31

### Added

- logo to readme
- template:dev command to serve template when developing
- sample report data for development
- description and example call to help output

## [v0.4.0] - 2020-10-28

### Added

- ackee email style
- option to change email style

### Changed

- separate email and json service into different commands

## [v0.3.1] - 2020-10-28

### Added

- keywords to package.json

### Changed

- change readme order and examples

### Removed

- start and dev commands from package.json

## [v0.3.0] - 2020-10-26

### Added

- include all data available through API in report

### Changed

- use ejs to render email html
- structure of data returned in report

## [v0.2.2] - 2020-10-26

### Fixed

- correctly calculate average duration of all domains

## [v0.2.1] - 2020-10-26

### Added

- use `-d all` to generate a report for all domains

## [v.2.0] - 2020-10-26

First release
