# Bob

Bob is a macOS menu bar app that turns any window into an AI workspace.

It appears next to the window you are using, understands the current app context, and runs task-focused agents without taking over your screen.

## Download

Download the latest release from the Releases page:

- [Latest release](https://github.com/1amageek/bob/releases/latest)

## What Bob Does

- Works beside the app window you are already using
- Uses a window-centric model instead of forcing a file-centric workflow
- Starts from rules, so the same actions can be triggered consistently
- Shows active tasks as cards in a floating workspace
- Keeps the app lightweight by living in the menu bar

## Current Status

Bob is in active development.

The first supported adapter targets Finder so Bob can understand file and folder context directly. Support for additional apps will expand over time.

## Install

1. Download the latest `.dmg` or `.zip` from Releases.
2. Move `Bob.app` to your Applications folder.
3. Open Bob.
4. Grant the permissions Bob needs for window observation and automation features when macOS asks.

## Basic Flow

1. Launch Bob from the menu bar.
2. Move to the app window you want to work with.
3. Shake the window to bring up Bob beside it.
4. Let Bob inspect context through the matching app adapter.
5. Review progress in the floating card stack.

## Documentation

- Product page: [GitHub Pages](https://1amageek.github.io/bob/)
- Usage guide: [Getting started](https://1amageek.github.io/bob/#getting-started)
- Roadmap: [GitHub Issues](https://github.com/1amageek/bob/issues)

## Publish The Site

This repository is prepared for GitHub Pages deployment through GitHub Actions.

1. Push this repository to `https://github.com/1amageek/bob`
2. In GitHub, open `Settings > Pages`
3. Set the source to `GitHub Actions`
4. Push to `main`
5. Wait for the `Deploy Pages` workflow to finish

The site will be published at:

- [https://1amageek.github.io/bob/](https://1amageek.github.io/bob/)

## Feedback

If you hit a bug or want to request support for another app, open an issue in this repository.
