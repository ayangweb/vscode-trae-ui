Hi, this is my attempt at trying to make VSCode look like Trae.

![](https://github.com/user-attachments/assets/c64130b8-70dd-4f0d-b119-4f75f37a91a4)

### Preparation

Install the [Trae Theme](https://marketplace.visualstudio.com/items?itemName=yoy0721.trae-theme) extension and select dark mode.
Install the [Seti File Trae Icon](https://marketplace.visualstudio.com/items?itemName=yanfeixin.king-trae-icon) extension.
Install the [Custom UI Style](https://marketplace.visualstudio.com/items?itemName=subframe7536.custom-ui-style) extension.

### How to Use

Download the `custom.css` file to your computer, then open VSCode's `settings.json` file and add the following content.

> Important Note: `file://` is mandatory, please do not attempt to remove it.

```json
"custom-ui-style.external.imports": [
    "file:///Users/xxxx/custom.css"
],
```
