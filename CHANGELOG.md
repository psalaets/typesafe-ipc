# Change Log

All notable changes to this project will be documented in this file.

## [2.0.0] - 2020-08-31

### Breaking Change

- Peer dependency requires Electron version `>=5.0.0` (was: `^4.0.1`)

### Added

- Type support for `webContents.sendToFrame()` (Electron 5+)

## [1.1.0] - 2020-08-31

### Added

- Exports a new type `StrictWebContents` which is a more strictly typed version of Electron's `WebContent`. This allows `webContents.send()` to be type checked.

## Starting point

Forked from https://github.com/orourkek/typesafe-ipc version 1.0.4
