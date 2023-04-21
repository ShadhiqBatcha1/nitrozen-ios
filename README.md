[![Swift](https://raw.githubusercontent.com/hitendra-gofynd/nitrozen-ios/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/Nitrozen-github-white.png)](https://raw.githubusercontent.com/hitendra-gofynd/nitrozen-ios/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/Nitrozen-github-white.png)

[![Swift](https://img.shields.io/badge/Swift-5%2B-blue)](https://img.shields.io/badge/Swift-5%2B-blue)
[![Platforms](https://img.shields.io/badge/Platforms-iOS-orange)](https://img.shields.io/badge/Platforms-iOS-orange)
[![Swift Package Manager](https://img.shields.io/badge/Swift_Package_Manager-compatible-orange?style=flat-square)](https://img.shields.io/badge/Swift_Package_Manager-compatible-orange?style=flat-square)

Nitrozen-SwiftUI is a UILibrary, includes a set of common UI elements such as buttons, text fields, checkbox, and radio, among others, but with a high degree of flexibility and modularity that allows developers to easily modify the components to meet their specific design needs. These customization options may include changing the colors, fonts, and styles of the components, as well as adjusting the layout and behavior of the user interface.

## Basic Building blocks
### a. Apperance
Apperance provide the styling to UI element/control like colors, fonts, radius, shapes, padding, etc.
[![Apperance](https://raw.githubusercontent.com/hitendra-gofynd/nitrozen-ios/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/Nitrozen-apperance-architecture.png)](https://raw.githubusercontent.com/hitendra-gofynd/nitrozen-ios/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/Nitrozen-apperance-architecture.png)


### b. UI Elements/Controls
That takes apperance as optional inputs for its styling, and other inputs as per its requirements. If optional apperance is not provided - it will use Appearance.shared.controlApperance for consistent styling.
[![Apperance](https://raw.githubusercontent.com/hitendra-gofynd/nitrozen-ios/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/Nitrozen-apperance-builder-pattern.png)](https://raw.githubusercontent.com/hitendra-gofynd/nitrozen-ios/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/Nitrozen-apperance-builder-pattern.png)


## Elements
* [Button](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeButton.md)
* [Text/Label/Font](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeTextLabelFont.md)
* [TextField](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeTextField.md)
* [Checkbox](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeCheckbox.md)
* [Radio](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeRadio.md)
* [Color Pallets](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeColors.md)
* [DropDown TextField](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeDropdownTextfield.md)
* [TagView](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeTagView.md)
* [Badge View](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeBadge.md)
* [Switch/Toggle](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeToggle.md)
* [Progress Stepper](https://github.com/hitendra-gofynd/nitrozen-ios/blob/master/Example-Nitrozen-SwiftUI/Example-Nitrozen-SwiftUI/Preview%20Content/ReadmeProgressStepper.md)


## Contributors

- [Hitendra Solanki](https://github.com/hitendradeveloper)
- [Rushang Prajapati](https://github.com/Rushang08)
- [Keyur Patel](https://github.com/KeyurPatel-1)


## Requirements

| Platform | Minimum Swift Version | Installation | Status |
| --- | --- | --- | --- |
| iOS 13.0+ | 5.0 | [Swift Package Manager](#swift-package-manager) | Fully Tested |

## How to install? - via Swift Package Manager

The  [Swift Package Manager](https://swift.org/package-manager/)  is a tool for automating the distribution of Swift code and is integrated into the  `swift`  compiler.

Once you have your Swift package set up, adding Nitrozen-SwiftUI as a dependency is as easy as adding it to the  `dependencies`  value of your  `Package.swift`.

```
dependencies: [
    .package(url: "https://github.com/gofynd/nitrozen-ios.git", branch: "master")
]
```

## How to Contribute?

1. Fork Repo and Create PR. 
2. We will review your PR, if PR will be merged successfully, your name will visible under the contributors list. Happy coding :)

## License

Nitrozen-SwiftUI is released under the MIT license.


