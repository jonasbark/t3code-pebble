# Changelog

## 0.1.7

- Fixed thread lists showing only "New thread" on current T3 Code nightlies, which send a second, thread-less shell snapshot after the real one.
- Going back from a project's threads now shows the cached project list instead of reloading it.

## 0.1.6

- Fixed the `WS ERROR` with current T3 Code nightlies by connecting with orchestration protocol 2.
- Updated project, thread, and message loading, working and completion indicators, thread creation, and sending for the protocol 2 data shapes, while keeping compatibility with older servers.

## 0.1.5

- Added project-level activity indicators so working agents are visible before opening a thread.
- Improved navigation with a responsive Back button during loading and smooth, layout-aware scrolling for long messages.
- Improved phone-to-watch reliability with request-scoped updates, UTF-8-safe message sizing, stale-response cleanup, and clearer delivery errors.
- Preserved project model selections and thread runtime and interaction modes when creating threads or sending prompts from the watch.
- Improved setup, controls, troubleshooting, and reproducible release documentation.
