# React Native Cocoapods Demo App

This app demos that setting up CocoaPods on a new react native app doesn't work out of the box.

```bash
react-native init CocoaPodsFailingDemo
cd CocoaPodsFailingDemo/ios
pod init
pod install
```

This fails with:

```bash
Analyzing dependencies
[!] The target `CocoaPodsFailingDemo-tvOSTests` is declared twice.
```