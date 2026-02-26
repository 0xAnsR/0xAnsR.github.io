# Changelog

All notable changes to this project will be documented in this file.

## [2.1.0] - 2026-02-26

### Added
- **Performance:** Native lazy loading (`loading="lazy"`) added to all 30+ images to optimize LCP and overall page speed.
- **Design:** Premium layered box-shadows implemented via CSS variables for consistent, high-end depth.
- **Interactivity:** Enhanced hover states with refined 3D transforms (`translateY`, `scale`) and `z-index` management.
- **Version Control:** Versioning info added to the footer for build tracking.

### Fixed
- **Input Blocking:** Resolved issue where the `particles-js` canvas overlay prevented mouse interactions and hover events on underlying cards.
- **Animation Conflicts:** Fixed transform collisions between scroll-triggered slide-in animations and hover transitions.

### Changed
- **Visuals:** Updated card architecture with `16px` border-radius and removed hard borders for a "soft UI" aesthetic.
- **Architecture:** Refactored CSS to use semantic variables for shadows, transitions, and radii.
