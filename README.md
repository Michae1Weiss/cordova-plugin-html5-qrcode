# cordova-plugin-html5-qrcode

A custom Cordova plugin to include the `html5-qrcode` library in your Cordova-based mobile application. This plugin bundles the JavaScript library locally, allowing offline QR code scanning without relying on external CDNs.

## Features

- **Offline QR code scanning:** No internet connection required.
- **Local bundling:** The `html5-qrcode` library is included as part of your app's assets.
- **Easy integration:** Simply include the plugin and reference the library in your HTML.

## Installation

To install the plugin, add it to your `config.xml` or install it via the Cordova CLI.

### 1. Add via `config.xml`

```xml
<plugin name="cordova-plugin-html5-qrcode" spec="https://github.com/your-username/cordova-plugin-html5-qrcode.git" />
