# Changelog

All notable changes to `dhlparcel-php-api` will be documented in this file.

## [Unreleased]

## [v1.4.0] - 2020-12-18

### Added
- Support for PHP 8. [`#60`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/60)

## [v1.3.1] - 2020-12-17

### Fixed
- Breaking change introduced by `lcobucci/jwt:^3.4`. [`#59`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/59)

## [v1.3.0] - 2020-09-17

### Changed
- Use PHP 7 types and return type declarations where possible. [`#55`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/55)
- The minimum version for `ramsey/uuid` is now ^4.0. [`091304e`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/091304edff77d9f547f497cdba4f2ad4736c70b0)

### Fixed
- Conflicts with the `collection` package. [`#56`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/56)

## [v1.2.1] - 2020-08-08

### Added
- Added support for `tightenco/collect` ^8.0 [`3b9eb55`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/3b9eb55a73c2f63afdba6031656578f4b967def6)

## [v1.2.0] - 2020-08-07

### Added
- Added support for an additional address line. [`#49`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/49)

## [v1.1.1] - 2020-06-28

### Added
- Added support for `guzzlehttp/guzzle` ^7.0. [`12afc81`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/12afc81b399de1553029866377bbe9331d4e3c78)

## [v1.1.0] - 2020-05-10

### Added
- Added Cash on Delivery delivery option. [`#48`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/48)

## [v1.0.1] - 2020-03-24

### Added
- Added support for `ramsey/uuid` ^4.0. [`41fffd1`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/41fffd1c930e8a4bb40dd3f3f607ff3821d2a87f)

## [v1.0.0] - 2020-02-26

### Added
- Added response to `DhlParcelException`. [`#47`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/47)

## [v0.8.2] - 2019-12-12

### Changed
- Make the country code for service point configurable. [`#40`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/40)

## [v0.8.1] - 2019-12-12

### Changed
- Allow `symfony/var-dumper` ^4.0. [`23c2ef2`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/23c2ef2699d5ec366ca9da41373b766fd30e464c)

## [v0.8.0] - 2019-12-03

### Added
- Added `pieces` to the `Shipments` resource. [`#37`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/37)
- Added `barcode` alias for `tracker_code` on the `ShipmentPiece` resource. [`#38`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/38)

### Changed
- Refactored `Pieces` resource to  a`PiecesCollection`. [`#35`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/35)

## [v0.7.0] - 2019-11-14

### Removed
- Removed support for Laravel. Please use this [package](https://github.com/mvdnbrk/laravel-dhlparcel) instead. [`#16`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/16)

## [v0.6.2] - 2019-11-14

### Added
- Added `ShipmentPiece` resource. [`#10`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/29)

## [v0.6.1] - 2019-11-13

### Fixed
- Make sure `quantity` and `weight` are integer values. [`#27`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/27)

## [v0.6.0] - 2019-11-13

### Added
- Added `ext-json` as a requirement. [`#23`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/23)

### Changed
- Changed `addPiece` method to `add` in the `Pieces` class. [`#19`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/19)
- Changed `company` to an alias for `company_name` in the `Recipient` class. [`#13`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/13)

## [v0.5.0] - 2019-11-11

### Added
- Added ability to set `pieces` for a parcel. [`#10`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/10)

## [v0.4.1] - 2019-11-11

### Changed
- Updated dependencies.

### Fixed
- Fixed missing import. [`484b5d4`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/484b5d43c9f5b3ae90baa034642a91ab2e4a3f0b)

## [v0.4.0] - 2019-10-08

### Changed
- Dropped support for PHP version 7.1.
- Updated dependencies.

## [v0.3.4] - 2019-04-12

### Added
- Added `setAccountId` method. [`#8`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/8)

## [v0.3.3] - 2019-03-20

- Fixed ServicePoint toArray(). [`a46bd0a`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/a46bd0a18cbd5bca6c80b2332eb068b7b5f4777a)

## [v0.3.2] - 2019-03-20

### Fixed
- Fixed use statement. [`4b9006f`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/4b9006f8e718b344d520cff8560a406cfa9d06ba)

## [v0.3.1] - 2019-03-20

### Changed
- The `toArray` method on a `ServicePoint` object has changed. [`#7`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/7)

## [v0.3.0] - 2019-03-19

### Added
- Added an option to send a parcel to a service point. [`#6`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/6)
- Added an endpoint to retrieve service point locations. [`#5`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/5)
- Added an `addition` alias to set a number suffix for an address. [`#4`](https://github.com/mvdnbrk/dhlparcel-php-api/pull/4)

## [v0.2.0] - 2019-03-15

### Added
- Added Track & Trace endpoint. [`cea132d`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/cea132dc316a683ecc8289f9c964eb8cdc9d47b1)

## [v0.1.2] - 2019-02-23

### Fixed
- Convert a shipment to an array correctly. [`91b2cb73`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/91b2cb73af77a097b596f950c48aa03705890f78)

## [v0.1.1] - 2019-02-23

### Fixed
- Fixed class import. [`bf990c4`](https://github.com/mvdnbrk/dhlparcel-php-api/commit/bf990c4447acae78e96f21a6cd49e57f45eb30dd)

## [v0.1.0] - 2019-02-22

### Initial release

[Unreleased]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v1.4.0...HEAD
[v1.4.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v1.3.1...v1.4.0
[v1.3.1]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v1.3.0...v1.3.1
[v1.3.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v1.2.1...v1.3.0
[v1.2.1]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v1.2.0...v1.2.1
[v1.2.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v1.1.1...v1.2.0
[v1.1.1]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v1.1.0...v1.1.1
[v1.1.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v1.0.1...v1.1.0
[v1.0.1]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v1.0.0...v1.0.1
[v1.0.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.8.2...v1.0.0
[v0.8.2]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.8.1...v0.8.2
[v0.8.1]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.8.0...v0.8.1
[v0.8.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.7.0...v0.8.0
[v0.7.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.6.2...v0.7.0
[v0.6.2]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.6.1...v0.6.2
[v0.6.1]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.6.0...v0.6.1
[v0.6.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.5.0...v0.6.0
[v0.5.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.4.1...v0.5.0
[v0.4.1]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.4.0...v0.4.1
[v0.4.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.3.4...v0.4.0
[v0.3.4]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.3.3...v0.3.4
[v0.3.3]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.3.2...v0.3.3
[v0.3.2]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.3.1...v0.3.2
[v0.3.1]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.3.0...v0.3.1
[v0.3.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.2.0...v0.3.0
[v0.2.0]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.1.2...v0.2.0
[v0.1.2]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.1.1...v0.1.2
[v0.1.1]: https://github.com/mvdnbrk/dhlparcel-php-api/compare/v0.1.0...v0.1.1
[v0.1.0]: https://github.com/mvdnbrk/dhlparcel-php-api/tree/v0.1.0
