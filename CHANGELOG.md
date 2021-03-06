# Change Log

## [0.3.0]

### Added

-   JSON Escape Assistant

### Changed

-   Only rename changed identifiers that intersect with the current selection. This prevents accidental renames.

## [0.2.3]

### Fixed

-   Repairs readme.

## [0.2.2]

### Added

-   Setting `hediet-power-tools.applyRename.theme`: Allows to customize how tracked identifiers are highlighted.

## [0.2.1]

### Fixed

-   Stack Frame Line Highlighter now works across multiple files.

## [0.2.0]

### Changed

-   Removes restriction to only rename 2 symbols at once.
-   Makes highlighting less obtrusive.
-   Adds code action to apply a rename.
-   Binds apply rename to shift+enter rather than F2.
-   Does not override shift+enter if the current selection does not intersect with the tracked spans.

### Added

-   Custom Definition feature
-   Stack Frame Highlight feature
-   Debug Adapter Logger Feature

## [0.1.1]

### Added

-   Binds escape to abort rename session

## [0.1.0]

-   Initial release
