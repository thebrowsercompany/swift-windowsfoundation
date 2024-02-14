# Swift Language Bindings for `Windows.Foundation` APIs

This repository contains the Swift/WinRT language bindings for types in the `Windows.Foundation` namespace. It also contains general helper APIs used throughout all generated bindings.

These APIs are intendened to be used in conjuction with the following projects:
- [swift-uwp](https://github.com/thebrowsercompany/swift-uwp)
- [swift-winui](https://github.com/thebrowsercompany/swift-winui)
- [swift-windowsappsdk](https://github.com/thebrowsercompany/swift-windowsappsdk)
- [swift-win2d](https://github.com/thebrowsercompany/swift-win2d)

## Filing Issues

Please file any issues you have with this repository on https://github.com/thebrowsercompany/swift-winrt

## Known Issues and Limitations
- The developer experience for consuming WinRT APIs from Swift is a work in progress. Due to current limitations, not all APIs can be generated as this causes export limit issues.

- The APIs listed in projections.json are required for the other `swift-*` projects to build. Modify a projections.json in any one of those projects could require an update here.
