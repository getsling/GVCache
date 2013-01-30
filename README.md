# GVCache
A clone of [EGOCache](https://github.com/enormego/EGOCache), but with the added method:

```objective-c
- (NSTimeInterval)ageForKey:(NSString *)key;
```

GVCache was created with a new name so a [CocoaPods](http://cocoapods.org) podspec could be shared independently from EGOCache.

# About EGOCache 2.0
EGOCache is a simple, thread-safe key value cache store. It has native support for NSString, UI/NSImage, and NSData, but can store anything that implements <NSCoding>. All cached items expire after the timeout, which by default, is one day.
