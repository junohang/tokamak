## 0.4.0
* Adds `atom-ide-ui` support.
* Fixes cargo view variable globing.
* Fixes #68 directory path problem on startup.
* Adds state checker for RLS.
* Adds RLS support for hover, click and go to definition.

## 0.3.2
* Fixes project specific launch. From now on if launchAlways box is checked it launches with global definition. If directory contains a cargo project with `tokamak.toml` it will load project-specific conf otherwise it loads global config.
* Fixes auto save problems

## 0.2.9
* Fixes startup error (hope...)

## 0.2.8
* Introduce tokamak project file
* Make Rustup default toolchain manager and add RustUp support (thanks to @zmanian)
* Auto formatting code and RustFmt support

## 0.2.7
* Save files on run/build/test
* Toolbar toggle added.
* Fix for cargo project dir handling

## 0.2.6
* Settings view in toolbar
* Fixes problem with about view
* Added terminal view
* Run and test commands

## 0.1.0

* Cargo commands implemented
* Creating cargo project implemented
* Multirust changing toolchain implemented
