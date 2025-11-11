Hi 👋, I’m trying to make VS Code look like the first version of Trae IDE’s UI. I’ll keep improving the style, so stay tuned for future updates!

![](https://github.com/user-attachments/assets/c64130b8-70dd-4f0d-b119-4f75f37a91a4)

### Preparation

Install the [Trae Theme](https://marketplace.visualstudio.com/items?itemName=yoy0721.trae-theme) extension and select dark mode.
Install the [Seti File Trae Icon](https://marketplace.visualstudio.com/items?itemName=yanfeixin.king-trae-icon) extension.
Install the [Custom UI Style](https://marketplace.visualstudio.com/items?itemName=subframe7536.custom-ui-style) extension.

### How to Use

Download the `custom.css` file to your computer, then open VSCode's `settings.json` file and add the following content.

> Important Note: `file://` is mandatory, please do not attempt to remove it.
> Please replace `xxx` with your own path.

```json
"custom-ui-style.external.imports": [
    "file://xxx/custom.css"
],
```

### Contributing

Please install the two plugins recommended by your IDE, as specified in [.vscode/extensions.json](.vscode/extensions.json), and then you can freely modify the custom.scss file.
