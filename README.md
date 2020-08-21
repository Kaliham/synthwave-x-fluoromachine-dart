# synthwave-x-fluoromachine-dart

This is a fork of @webrender [synthwave-x-fluoromachine](https://github.com/webrender/synthwave-x-fluoromachine) (which is a fork of @robbowen's [Synthwave '84 theme](https://marketplace.visualstudio.com/items?itemName=RobbOwen.synthwave-vscode), merged with @fullerenedream's [Fluoromachine](https://colorsublime.github.io/themes/FluoroMachine/) theme for VSCode.).

In short this works with dark better than the original one :), and works on other langs(but designed for dart).

![Theme screenshot](./screen_shot.png)

## Installation

• install this theme  
• install [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)  
• link the CSS file from this extension in your vscode settings.json:

```
On Mac it might look something like the snippet below:

{
  "vscode_custom_css.imports": [
    "file:///Users/{your username}/.vscode/extensions/webrender.synthwave-x-fluoromachine-0.0.12/synthwave-x-fluoromachine.css"
    ]
}

Windows might resemble:

{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{your username}/.vscode/extensions/webrender.synthwave-x-fluoromachine-0.0.12/synthwave-x-fluoromachine.css"
    ]
}
```

• From the command panel, select `Reload Custom CSS and JS`. You'll need to run this command every time vscode updates.
