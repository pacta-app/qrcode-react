# qrcode-react

This is a fork of [cssivision/qrcode-react](https://github.com/cssivision/qrcode-react) with the only intention to remove hard coded style and attributes. The stiling should be done with selectors in css files and must not be implemented hard coded.

A React component to generate [QRCode](http://en.wikipedia.org/wiki/QR_code) with logo.
Inspired by [zpao/qrcode.react](https://github.com/zpao/qrcode.react), also support chinese.

## Installation

```sh
npm install pacta-app/qrcode-react
```

## Usage

```js
var React = require("react");
var ReactDOM = require("react-dom");
var QRCode = require("pacta-app/qrcode-react");

ReactDOM.render(<QRCode value="http://facebook.github.io/react/" />, mountNode);
```

## Available Props

| prop         | type                  | default value                       |
| ------------ | --------------------- | ----------------------------------- |
| `value`      | `string`              | `http://facebook.github.io/react/`  |
| `size`       | `number`              | `128`                               |
| `bgColor`    | `string` (CSS color)  | `"#FFFFFF"`                         |
| `fgColor`    | `string` (CSS color)  | `"#000000"`                         |
| `logo`       | `string` (URL / PATH) |
| `logoWidth`  | `number`              | `size * 0.2`                        |
| `logoHeight` | `number`              | Proportional scaling to `logoWidth` |

<img src="qrcode.png" height="256" width="256">
