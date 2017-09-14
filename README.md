# YAJL 2.1.0 Dynamic Framework

[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

This repository contains source code from [YAJL](https://github.com/lloyd/yajl) 2.1.0 and is configured as a **dynamic framework for iOS** in an Xcode project so that it can be built with Carthage. It was tested with Xcode 9.0.

The framework target has "Require Only App-Extension-Safe API" set to "Yes" to support linking with app extensions.

## Install with Carthage

Install Carthage with [Homebrew](https://brew.sh):

    $ brew install carthage

Integrate YAJL into your Xcode project by adding this to your `Cartfile`:

    github "adblockplus/yajl-dynamic" ~> 1.0

Run `carthage update` to build the framework. Drag the built framework into
your Xcode project.
