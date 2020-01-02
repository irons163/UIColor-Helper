# UIColor-Helper

- UIColor-Helper is a useful and light color tool for iOS.

Functions:
```objc
+ (UIColor *)colorWithColorCodeString:(NSString *)colorString;
+ (UIColor *)colorWithARGB:(NSUInteger)color;
+ (UIColor *)colorWithRGB:(NSUInteger)color;
+ (UIColor *)colorWithRGBA:(NSUInteger)color;
+ (UIColor *)colorWithRGBWithString:(NSString *)colorString;
```

The most common use way:
```objc
#import "UIColor+Helper.h"

#define ErrorRedColor @"EF4257"

[UIColor colorWithColorCodeString:ErrorRedColor];
```
