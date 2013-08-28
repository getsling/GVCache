# GVCache
A clone of [EGOCache](https://github.com/enormego/EGOCache), but with the added method:

```objective-c
- (NSTimeInterval)ageForKey:(NSString *)key;
```

This method makes it possible to create a "rolling cache", exactly as we do with the [LastFm library](https://github.com/gangverk/LastFm) in Last.fm's [Scrobbler for iOS](http://www.last.fm/hardware/ios) app.

GVCache was created with a new name so a [CocoaPods](http://cocoapods.org) podspec could be shared independently from EGOCache.

## Deprecated
EGOCache has added a new `dateForKey:` method since I've created  GVCache. I would thus suggest that you'd use EGOCache.


# About EGOCache 2.0
EGOCache is a simple, thread-safe key value cache store. It has native support for NSString, UI/NSImage, and NSData, but can store anything that implements <NSCoding>. All cached items expire after the timeout, which by default, is one day.
