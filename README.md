# Peaberry

This repository holds the website for [Peaberry](https://peaberry.ctsite.cc/), a macOS menu bar app that lets AI agents keep the Mac awake while they work and gives sleep back to your settings when they are done, and its issue tracker.

The app's source code is not published here. Peaberry comes from the Mac App Store.

## Help, bugs and requests

Open an issue: <https://github.com/tasict/Peaberry/issues>

It helps to include:

- your macOS version and Peaberry version (Settings › About)
- what you expected and what happened instead
- the output of `/Applications/Peaberry.app/Contents/MacOS/Peaberry --brief`, and what the Diagnostics tab in Settings says

Issues are public, so leave out anything you would not want others to read.

## The website

Plain static HTML and one stylesheet, in four languages (English, 繁體中文, 日本語, Español), served by GitHub Pages at <https://peaberry.ctsite.cc/>. There is no build step: what is in this repository is what the site serves. The screenshots and menu bar images in `assets/` are rendered from the app itself and committed here when the site is published. Please report problems with the site as issues too.

- [Privacy policy](https://peaberry.ctsite.cc/privacy.html)

© 2026 tasict
