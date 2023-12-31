# WinAppUI
SwiftUI-like framework for writing WinUI apps using Swift (using bindings from https://github.com/thebrowsercompany)
## Why WinAppUI
When [The Browser Company](https://github.com/thebrowsercompany) published their [Swift bindings for WinRT/WinAppSDK/WinUI](https://github.com/thebrowsercompany/swift-winrt) (ah, the joys of Windows development), it finally meant that you could write Windows apps using Swift! Unfortunately, you're still writing a Windows app, and you still have all of the problems associated with writing a Windows app. Namely, state is notoriously complicated and dealing with state changes means writing ~10 more lines of code than is *truly* necessary. Apple solved this in 2019 with SwiftUI, arguably the best app development framework imaginable. The problem is that it is only available on iOS, macOS, watchOS, tvOS and sort of [the web](https://github.com/TokamakUI/Tokamak). Using The Browser Company's Swift bindings as a base, WinAppUI aims to implement something *like* SwiftUI for Windows.
> [!WARNING]  
> While WinAppUI aims to mostly reimplement SwiftUI for Windows: **it won't be perfect**, and it won't be immediately compatible with SwiftUI without **code changes**.
(todo: literally the rest of the documentation)
