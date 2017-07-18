# PGNumberKeyboard
一款非常简单漂亮灵活的自定义数字键盘

![](http://upload-images.jianshu.io/upload_images/1340308-51b3385a24317812.gif?imageMogr2/auto-orient/strip)

# Installation with CocoaPods
```
pod 'PGNumberKeyboard'
```

# Usage

> UITextField

```
#import <PGNumberKeyboard/PGNumberKeyboard.h>

self.yourTextField.inputView = [[PGNumberKeyboard alloc]initWithTextField:self.yourTextField];
```
> UITextView

```
self.yourTextView.inputView = [[PGNumberKeyboard alloc]initWithTextView:self.yourTextView];
```


# Advanced Usage

> UITextField

```
PGNumberKeyboard *keyboard = [[PGNumberKeyboard alloc]initWithTextField:self.yourTextField];
keyboard.delegate = self;
self.yourTextField.inputView = keyboard;

#pragma mark - PGNumberKeyboardManagerDelegate

- (void)editChanage:(id)sender {
}

```
> UITextView

```
PGNumberKeyboard *keyboard = [[PGNumberKeyboard alloc] initWithTextView:self.yourTextView];
keyboard.delegate = self;
self.yourTextView.inputView = keyboard;

#pragma mark - PGNumberKeyboardManagerDelegate

- (void)editChanage:(id)sender {
}

```

# Overview
[http://www.jianshu.com/p/d6455564675e
](http://www.jianshu.com/p/d6455564675e)

