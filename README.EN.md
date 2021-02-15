# QTalk IM SDK
## Overview
Provides IM communication capabilities, including single chat, group chat, notification push. Support sending text, images, emoticons, voice, files, geolocation .... Support audio and video calls.
## Project structure

* QIMCommonCategories (extended class components)
* QIMDataBase (database component, depends on sqlite3)
* QIMOpenSSL (UI module)

## Integration

### CocoaPods
1. Add `source 'https://github.com/qunarcorp/libqimkit-ios-cook.git'`
2. Add `pod 'QIMDataBase'` to your Podfile.
3. Add `pod 'QIMOpenSSL'` to your Podfile.
4. Add `pod 'QIMCommonCategories'` to your Podfile.
Run `pod install` or `pod update`.

## Problem Feedback

- app@startalk.im (email)
