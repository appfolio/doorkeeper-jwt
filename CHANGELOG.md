# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.2.1] - 2017-06-07
### Fixed
- The `token_headers` proc now passes `opts` like the other config methods. Fixed via #19 by @travisofthenorth.

## [0.2.0] - 2017-05-25
### Added
- Added support for ["kid" (Key ID) Header Parameter](https://tools.ietf.org/html/rfc7515#section-4.1.4) @travisofthenorth. Allows custom token headers.
