# ViewGraph-Releases

Public release artifacts for ViewGraph, a macOS app for understanding SwiftUI
projects.

ViewGraph analyzes SwiftUI projects and helps you understand how screens,
components, navigation, previews, and code changes relate to each other. It runs
locally on your Mac.

## Latest release: 0.1.0-alpha.4

- Browse, select, and export every preview variation for screens, components,
  and widgets.
- Widget previews use the correct WidgetKit family and rendering mode, with a
  configurable background and dedicated widget image export.
- A unified **Export All Previews** flow lets you choose exactly which images to
  include before exporting.
- Previews render for nested Xcode projects in multi-project folders, including
  SwiftUI template projects.
- More reliable preview generation: function-based preview helpers keep their
  required inputs, usage previews resolve environment values proven from source,
  and the Swift 6 batch preview host no longer relaunches per preview.
- Preview variant switching, cache reuse, and cancellation are fixed in the
  inspector, and working-tree Swift changes reload automatically.

Download `ViewGraph-0.1.0-alpha.4.dmg` from the
[0.1.0-alpha.4 release](https://github.com/coper101/ViewGraph-Releases/releases/tag/v0.1.0-alpha.4),
then verify it with the published `.sha256` sidecar.

This is an early public alpha. It requires macOS 15.0 or later; preview
workflows require Xcode 16 or later.

## Releases

See the [releases page](https://github.com/coper101/ViewGraph-Releases/releases)
for all published prereleases and checksums.
