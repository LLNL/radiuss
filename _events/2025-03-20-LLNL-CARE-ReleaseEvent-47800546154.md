---
event_type: ReleaseEvent
avatar: "https://avatars.githubusercontent.com/u/6393677?"
user: adayton1
date: 2025-03-20
repo_name: LLNL/CARE
html_url: https://github.com/LLNL/CARE/releases/tag/v0.15.0
repo_url: https://github.com/LLNL/CARE
---

<a href='https://github.com/adayton1' target='_blank'>adayton1</a> released <a href='https://github.com/LLNL/CARE/releases/tag/v0.15.0' target='_blank'>v0.15.0</a>.

<small>## Release date 2025-03-20

### Added
- Added CARE\_DEEP\_COPY\_RAW\_PTR configuration option.
- Added ATOMIC\_SUB, ATOMIC\_LOAD, ATOMIC\_STORE, ATOMIC\_EXCHANGE, and ATOMIC\_CAS macros.

### Removed
- Removed Accessor template parameter from host\_device\_ptr.
- Removed NoOpAccessor and RaceConditionAccessor. It is recommended to use ThreadSanitizer (TSAN) instead to locate race conditions.
- Removed CARE\_ENABLE\_RACE\_DETECTION configuration option.
- Removed implicit conversions between raw pointers and host\_device\_ptrs/host\_ptrs and the corresponding CARE\_ENABLE\_IMPLICIT\_CONVERSIONS configuration option.

### Changed
- Renamed host\_device\_ptr::getPointer to host\_device\_ptr::data.

### Fixed
- Replaced calls to chai::ManagedArray::getPointer (previously deprecated and now removed) with calls to chai::ManagedArray::data.

### Updated
- Updated to BLT v0.7.0
- Updated to Umpire v2025.03.0
- Updated to RAJA v2025.03.0
- Updated to CHAI v2025.03.0

**Full Changelog**: https://github.com/LLNL/CARE/compare/v0.14.1...v0.15.0</small><a href='https://github.com/LLNL/CARE/releases/tag/v0.15.0' target='_blank'>View Comment</a>