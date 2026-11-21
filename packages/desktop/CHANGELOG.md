# @e2e-dev/desktop

## 0.0.1

### Patch Changes

- [#1953](https://github.com/e2e-inc/e2e/pull/1953) [`a2d0363`](https://github.com/e2e-inc/e2e/commit/a2d0363128c95288b8e43d50029dc7a14b40c002) Thanks [@kdy1](https://github.com/kdy1)! - New package: `@e2e-dev/desktop`, the desktop engine. `engine: desktop()` drives a native app on macOS through agent-desktop's accessibility commands: observation, the `screen` locators and actions, test ids, secret fills over stdin, masked screenshots, and the `desktop` fixture. The app runs in the background and gets only a few variables of the run's environment. The engine downloads its pinned agent-desktop release on the first run.
