This repo is to demonstrate a problem with the keyboard on iOS with Capacitor integration.

I have an issue in an Ionic 4 project, which affects iOS 11.0.1 but not iOS 11.4 or iOS 12.*.

When opening the keyboard (simply as a result of focusing an ion-input, not programmatically), the viewport is shrunk by the same height as the keyboard, TWICE. Let's say the viewport has a height  of 667px and the keyboard has a height of 216 px, then when the keyboard opens, the viewport height shrinks to 235 px.

Notes
Blue is ion-content, green is body.
![iOS screengrab](https://files.slack.com/files-pri/T89FW6TLL-FGBMRC7QQ/simulator_screen_shot_-_iphone_6s_-_2019-02-20_at_23.16.35.png)