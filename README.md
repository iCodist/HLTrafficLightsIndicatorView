# HLTrafficLightsIndicatorView

[![Version](https://img.shields.io/cocoapods/v/HLTrafficLightsIndicatorView.svg?style=flat)](http://cocoapods.org/pods/HLTrafficLightsIndicatorView)
[![License](https://img.shields.io/cocoapods/l/HLTrafficLightsIndicatorView.svg?style=flat)](http://cocoapods.org/pods/HLTrafficLightsIndicatorView)
[![Platform](https://img.shields.io/cocoapods/p/HLTrafficLightsIndicatorView.svg?style=flat)](http://cocoapods.org/pods/HLTrafficLightsIndicatorView)

## Example

### Result
<img src="Img/result.gif" alt="Animated gif">

### Layers
<img src="Img/layers.png" alt="Animated gif">

### Timeline
<img src="Img/timeline.png" alt="Animated gif">


## Requirements
- Swift 3.0
- iOS 8.0+
- Xcode 8.0

## Installation

HLTrafficLightsIndicatorView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod "HLTrafficLightsIndicatorView"
```

## Usage example

Inited from pure code ：

```swift
let view = HLTrafficLightsIndicatorView(frame: CGRect(x: 100, y: 100, width: 200, height: 200))
        
self.view.addSubview(view)
        
```
### Customization Properties

```swift

open var topRingColor        = UIColor.red
open var centerRingColor     = UIColor(red: 255/255, green: 192/255, blue: 1/255, alpha: 1)
open var bottomRingColor     = UIColor(red: 18/255, green: 222/255, blue: 125/255, alpha: 1)

open var duration: Double = 1.2 
```    

## TODO
The runway layer need enable spring animation.

## Author

pandaape, whailong2010@gmail.com

## License

HLTrafficLightsIndicatorView is available under the MIT license. See the LICENSE file for more info.
