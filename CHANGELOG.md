# Changelog

All notable changes to this project will be documented in this file.

The format is inspired by Keep a Changelog, and this project adheres to Semantic Versioning where practical.

## [v1.154.1] - 2025-11-16

### Changed
- Card values are easier to read when placed over player frames and cards:
  - Switched numbers to black, non-bold font for cleaner look
  - Added light text-shadow and a subtle semi-transparent white plate
  - Keeps legibility across varied backgrounds
- "Start New Round" button is now orange and blinks on page load to draw attention; blink stops on click.

### Fixed
- Prevented CSS/script for the start button from rendering as plain text on the table by moving it into proper `<style>`/`<script>` tags.
- Updated document title to match version: `Nine Card - Fast Speed v1.154.1`.

---

Older changes are available in commit history.

[v1.154.1]: https://github.com/mccaslin80-lab/nine-card-knockout/releases/tag/v1.154.1
