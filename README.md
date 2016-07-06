[![License MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://raw.githubusercontent.com/chisj/WSTabBarController/master/LICENSE)&nbsp;
[![Support](https://img.shields.io/badge/support-iOS%208%2B-blue.svg)](https://www.apple.com/nl/ios/)&nbsp;

# PopMenu
A animated PopMenu for the iOS app in Swift.

![Rise](ScreenShot/rise.gif)

![Diffuse](ScreenShot/diffuse.gif)


## Requirements

- iOS 8.0+
- Swift 2.2

## Installation


## Usage

```
let popMenu = PopMenu(frame: self.window!.bounds, item: itemArray);
popMenu.type = .Diffuse;
                
popMenu.itemClicked = { tag in
    print("the \(tag)'s item was clicked.");
}

popMenu.showMenuAtView(self.window!);

```

have fun !

## Addition

use [WSTabBarController](https://github.com/chisj/WSTabBarController) to finish the demo proj.

## License

PopMenu is available under the MIT license. See the LICENSE file for more info.
