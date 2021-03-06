# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## 1.4.0 - 2020-06-07

### Added

-   Implemented `ClearPastDueGracePeriods` to handle `grace_period_ends_at` expirations

### Changed

-   Delete subscription information after it has expired

## 1.3.1 - 2020-05-11

### Fixed

-   Use correct Facade FQCN

## 1.3.0 - 2020-05-11

### Changed

-   Removed Laravel 6 Support

## 1.2.3 - 2020-05-11

### Changed

-   Force `kodekeep/paddle-sdk` to be at least `1.1.0`

## 1.2.2 - 2020-04-04

### Added

-   `ClearPastDueTrials` command

## 1.2.1 - 2020-03-24

### Fixed

-   Access paddle.vendor_app instead of vendor_app

## 1.2.0 - 2020-03-24

### Added

-   Added `KodeKeep\Paddle\Billing\Concerns\Billabled`
-   Added `KodeKeep\Paddle\Billing\Listeners\CreateSubscriptionInformation`
-   Added `KodeKeep\Paddle\Billing\Listeners\DeleteSubscriptionInformation`
-   Added `KodeKeep\Paddle\Billing\Listeners\UpdateSubscriptionInformation`

## 1.1.3 - 2020-03-08

## Added

-   Added `KodeKeep\Paddle\Billing\PaddleInvoice` class for Cashier like behaviour

## 1.1.2 - 2020-03-08

## Added

-   Added `KodeKeep\Paddle\Facades\Paddle` facade

## 1.1.1 - 2020-03-07

## Fixed

-   Dispatch via `Event` facade

## 1.1.0 - 2020-03-03

### Added

-   Laravel 7 Support

## 1.0.0 - 2020-02-21

-   initial release

[unreleased]: https://github.com/kodekeep/laravel-paddle/compare/master...develop
