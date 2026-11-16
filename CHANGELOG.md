## Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog, and this project adheres to Semantic Versioning.

### [Unreleased]
- Improve docs, add more samples and screenshots
- CI build and lint workflow (planned)

### [v1.1.0] - 2026-11-16
#### Added
- Continuous, unified visual styling for range selections across calendar rows
- Animated range highlight that travels from the start date to the end date
- Optional repeating range animation via `repeatRangeLightAnimation(true)`
- Bounce feedback when selecting a day
- Fast month picker by tapping the displayed month
- Paginated year picker for quickly navigating to much earlier or later years
- Distinct split-circle indicator for a same-day range
- Configurable `todayButtonTextSize` in `PersianDatePickerStyle`

#### Changed
- Centered picker title with a fixed close button at the top-right
- Improved Today button sizing for smaller screens
- Improved range endpoint connections and RTL row wrapping

### [v1.0.0] - 2025-01-01
#### Added
- Android Persian (Jalali) DatePicker for Jetpack Compose
- Selection modes: Single, Multiple, Range
- Presentations: Dialog, Bottom Sheet with gravity (Top/Center/Bottom)
- Fully customizable `PersianDatePickerStyle` (colors, sizes, typography, ripple)
- Today button (custom text/callback) with calendar auto-navigation
- Optional Year Picker (grid columns, range years, styling)
- Selection summary footer
- Builder-based API: size/sizeFraction, margins, paddings, dismiss behaviors
- `SelectionResult` sealed class (Single/Multiple/Range)

[Unreleased]: https://github.com/Miaadrajabi/persianDatePicker/compare/v1.1.0...HEAD
[v1.1.0]: https://github.com/Miaadrajabi/persianDatePicker/compare/v1.0.0...v1.1.0
[v1.0.0]: https://github.com/Miaadrajabi/persianDatePicker/releases/tag/v1.0.0


