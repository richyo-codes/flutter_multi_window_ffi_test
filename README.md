# flutter_multi_window_ffi_test

This sample demonstrates Flutter Linux multi-window and popup behavior using
native GTK APIs through Dart FFI. It is intended to exercise both GTK3 and
GTK4 runners, including API branches needed because GTK4 changed several
windowing APIs around its post-Wayland model.

The popup path has been validated with both GTK3 and GTK4 native APIs. The GTK
variant check is intentionally local to this demo; Flutter should eventually
expose a better Linux GTK variant/version API for app and package code.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
