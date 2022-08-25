# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to
[Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

 - Added `#[must_use]` to all side-effect free functions.

## [0.3.0]

### Removed

 - Drop dependency on `rand`.

## [0.2.4]

### Removed

 - Yanked due to breaking change.

## [0.2.3]

### Changed

 - Update `rand` from `0.7.3` to `0.8.3`.

## [0.2.2]

### Changed
 
 - Update `rand` from `0.5.5` to `0.7.3`.

## [0.2.1]

### Changed

 - Reduce memory size of `VecList` from 96 bytes to 64. Tradeoff is max capacity is now reduced by 1 and a very slight
   performance decrease.

## [0.2.0]

### Changed

 - Change `VecList::retain` to give mutability to entries.

## [0.1.5]

### Added

 - Add unsafe removal function `VecList::remove_sync`. See its documentation for details.

## [0.1.4]

### Changed

 - Remove unnecessary `Debug` bounds.

## [0.1.3]

### Fixed

 - Fix possible overflow when incrementing generation.
 - Fix underflow when calling `pack_to_fit` on an empty `VecList`.

## [0.1.2]

### Added

 - Make iterator `iter` functions public.

## [0.1.1]

### Changed

 - Iterator optimizations.

## [0.1.0]

### Added

 - Initial release.
