# Lucky Patcher - Pixel Launcher - Disable Google Search

A Lucky Patcher patch to disable Google Search in the Pixel Launcher, and search apps only instead.

## Installation

Use Lucky Patcher's custom patch repository, or copy the .txt patch file (not .src.txt) to Lucky Patcher's CustomPatches directory on your device.

## Development

This patch does two things:

1. Use the app drawer search behaviour for the home screen search bar
2. Return `false` in the Google Search method, indicating a failure, and causing the fallback app drawer search UI to be used.

Everything is fully documented in the .src.txt file.

## Disclaimer

Lucky Patcher has a reputation as a piracy tool, but it is a piracy tool in the same way that a pocket knife is a weapon: It can be used for
piracy, but it has many other great features, including the ability to directly modify app code. This patch does not use any piracy.
