# keyboard-padding-capacitor

This repo is to demonstrate a problem with the keyboard on iOS with Capacitor integration.

## Description
I have an issue in an Ionic 4 project, which affects iOS 11.0.1 but not iOS 11.4 or iOS 12.*.

When opening the keyboard (simply as a result of focusing an ion-input, not programmatically), the viewport is shrunk by the same height as the keyboard, TWICE. Let's say the viewport has a height  of 667px and the keyboard has a height of 216 px, then when the keyboard opens, the viewport height shrinks to 235 px.

![iOS screengrab](https://github.com/sebastienguillon/keyboard-padding-capacitor/blob/master/iOS-11.0.1-capacitor.png)

**Note:** Blue is ion-content, green is body.

[The exact same Ionic code is used with a Cordova intagration.](https://github.com/sebastienguillon/keyboard-padding-cordova)
