<p align="center">
  <img src="https://github.com/shoheiyokoyama/Assets/blob/master/Gemini/logo.png" width="500">
</p>

# Overview

<img src="https://github.com/shoheiyokoyama/Assets/blob/master/Gemini/demo-circle-rotation.gif" align="left">

## What is the `Project`?

`Project` is Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras ut porttitor risus, in ultricies arcu. Donec justo ligula, faucibus sed gravida sit
amet, pulvinar a leo. Ut porta volutpat sem non tempor. Mauris sit amet arcu vitae justo blandit semper. Ut faucibus vestibulum pulvinar.
Praesent hendrerit dapibus dolor nec volutpat. Vivamus tristique rutrum convallis. Praesent dignissim sed est ut pharetra. Donec
hendrerit ante eget lorem aliquet lacinia. Vivamus vel quam ut ante eleifend maximus a in est. Donec id nisi tincidunt, aliquam augue et,
pretium ligula. Sed gravida in justo id iaculis. Vestibulum at quam a ligula rhoncus fermentum.

```python
def main()
    text = "Hello World!"
    return text

if __name__ == '__main__':
    text = main()
    print(text)
```

# Features

![Platform](http://img.shields.io/badge/platform-ios-blue.svg?style=flat
)
[![Cocoapods](https://img.shields.io/badge/Cocoapods-compatible-brightgreen.svg)](https://img.shields.io/badge/Cocoapods-compatible-brightgreen.svg)
[![Carthage compatible](https://img.shields.io/badge/Carthage-Compatible-brightgreen.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](http://img.shields.io/badge/license-MIT-lightgrey.svg?style=flat
)](http://mit-license.org)
![Swift](https://img.shields.io/badge/swift-5.0-orange.svg)
![pod](https://img.shields.io/badge/pod-v1.4.0-red.svg)

<img src="https://github.com/shoheiyokoyama/Assets/blob/master/Gemini/demo-yaw-rotation.gif" align="right">

- [x] Rich animation with scrolling
- [x] Easily usable
- [x] Highly customizable
- [x] Several types of animations and properties
- [x] Supports vertical and horizontal flow layout
- [x] Supports easing function
- [x] Supports `Swift5.0`
- [x] Fluent interfaces based on method chaining
- [x] Compatible with `Carthage`
- [x] Compatible with `CocoaPods`
- [x] Example project with lots of stock animations
- [x] And More...

# Contents

- [Animation Types and properties](#anmation-types)
- [Usage](#usage)
- [Requirements](#requirements)
- [Installation](#installation)
- [License](#license)
- [Author](#author)

# <a name="anmation-types"> Animation Types and properties

The following animation types are available. See sample code [here](https://github.com/shoheiyokoyama/Gemini/tree/master/Example/Gemini) for details.

- [Cube](#cube)
- [Circle Rotation](#circle-rotation) You can configure direction of rotation using the `CircleRotationDirection`
- [3D vector rotation](#3d-vector-rotation) Each rotation types provide multiple rotation effect
  - [Roll Rotation](#roll-rotation)
  - [Pitch Rotation](#pitch-rotation)
  - [Yaw Rotation](#yaw-rotation)
- [Scale](#scale)
- [Custom](#custom) You can create your own custom scroll animation using multiple properties, rotation, scale, translation, etc.

In addition, you can also customize the following properties for the above animation types.

- BackgroundColor
- CornerRadius
- Alpha
- [Easings](#easing-function)
- [Shadow Effect](#shadow-effect)

# <a name="usage"> Usage

1. ***Use Gemini classes***

`Gemini` is designed to be easy to use. Use `GeminiCollectionView` and `GeminiCell`. These classes is subclass of `UICollectionView`, `UICollectionViewCell`.

2. ***Configure animation***

Configure animation with fluent interface based on method chaining. You can develop expressive code that enhances readability.

3. ***Call function for animation***

Finally, call `animateVisibleCells()` in `scrollViewDidScroll(_:)`

> NOTE: If you want to adapt animation immediately after view is displayed, call `animateCell(_:)` in `collectionView(_:cellForItemAt:)` and `collectionView(_:willDisplay:forItemAt:)`.

```python
def func(arg):
    return arg

func(input())
```

## <a name="requirements"> Requirements

- Xcode 10.2.1
- Swift 5.0

## <a name="installation"> Installation

Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## <a name="license"> License

*Project* is available under the MIT license. See the [LICENSE](https://github.com/shaurya-src/repo-template/blob/main/LICENSE) for more info.

## <a name="author"> Author

```python
# Shaurya Choudhary
```

<!---
- [Gmail](mailto:shaurya.src@gmail.com)
- [GitHub](https://github.com/shoheiyokoyama)
- [LinkedIn](https://www.linkedin.com/in/shaurya-src/)
- [Instagram](https://www.instagram.com/shaurya_src/)
- [Twitter](https://twitter.com/shaurya_src)
-->

<p align="center">
  <a href="mailto:shaurya.src@gmail.com">
    <img src="https://github.com/shaurya-src/repo-template/blob/main/Assets/Logos/email.svg" width="30" height="30" hspace="20">
  </a>

  <a href="https://github.com/shaurya-src">
    <img src="https://github.com/shaurya-src/repo-template/blob/main/Assets/Logos/github.svg" width="30" height="30" hspace="20">
  </a>

  <a href="https://www.linkedin.com/in/shaurya-src/">
    <img src="https://github.com/shaurya-src/repo-template/blob/main/Assets/Logos/linkedin.svg" width="30" height="30" hspace="20">
  </a>

  <a href="https://www.instagram.com/shaurya_src/">
    <img src="https://github.com/shaurya-src/repo-template/blob/main/Assets/Logos/instagram.svg" width="30" height="30" hspace="20">
  </a>

  <a href="https://twitter.com/shaurya_src">
    <img src="https://github.com/shaurya-src/repo-template/blob/main/Assets/Logos/twitter.svg" width="30" height="30" hspace="20">
  </a>
</p>
