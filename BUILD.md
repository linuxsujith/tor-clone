# Build Onion Browser 3.X
## Build Dependencies

Onion Browser uses [CocoaPods](https://cocoapods.org/) as its dependency manager.


## Steps to build Onion Browser 3.X

```bash
git clone git@github.com:OnionBrowser/OnionBrowser.git
cd OnionBrowser
git checkout 3.X
pod repo update
pod install
open OnionBrowser.xcworkspace
