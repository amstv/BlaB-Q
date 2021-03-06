# BlaB! Q


BlaB! Q is a PhoneGap app (Android/IOS) for [BlaB! AX](https://justblab.com), [BlaB! AX Pro](https://justblab.com), [BlaB! WS](https://justblab.com) and [BlaB! WS Pro](https://justblab.com) chats. Your website visitors simply scan a QR code from the app **once** and then join the chat. The app allows you to have native sound notifications via the PhoneGap media plugin - playing audio/video automatically is disabled in mobile browsers. The back button triggers a prompt to exit the app.

![Alt text](/bwsq.png "void")
![Alt text](/bwsqe.png "void")

## QR code

You can create a QR code image easily using any of the online QR generators. The QR code should start with `blabws:` and end without a trailing slash - `blabws:https://YOURSITE.COM/chat`


## Permissions

The app lists `phone`, `microphone`, `storage` and `camera` - it is a PhoneGap media plugin requirement. You only need to enable `camera` in order to scan the QR code.


## License

MIT

## Links

* Website: https://justblab.com
* GitHub: https://github.com/uuencode/BlaB-Q
* Google Play: https://play.google.com/store/apps/details?id=com.justblab.bwsq
