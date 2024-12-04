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
<plugin name="cordova-plugin-html5-qrcode" spec="https://github.com/Michae1Weiss/cordova-plugin-html5-qrcode.git" />
```

### 2. Add via Cordova CLI

```bash
cordova plugin add https://github.com/your-username/cordova-plugin-html5-qrcode.git
```

## Usage

After installing the plugin, reference the `html5-qrcode.min.js` script in your `index.html`:

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>My Cordova App</title>
  <!-- Reference the locally bundled script -->
  <script src="js/html5-qrcode.min.js"></script>
</head>
<body>
  <!-- Your app content -->
</body>
</html>
```

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue for any improvements or bug fixes.

## License

This plugin is licensed under the Apache 2.0 License.