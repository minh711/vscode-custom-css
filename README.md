# Custom CSS for customizing VSCode

<img width="2046" height="1287" alt="image" src="https://github.com/user-attachments/assets/dc091985-226c-48a2-8fb0-a197698676b3" />

## Features

1. Border for each file on workspace.
2. Border for explorer panel.
3. Better highlight on focused file's tab.
4. ***Change VSCode UI font.***

## Installation

I used this extension:

![image](https://github.com/user-attachments/assets/39561cf5-2e6a-4009-a1b9-dd5639f92c6c)

After that, put the `custom.css` file in the right directory and change it in `settings.json`:

> I included paths for Windows, Linux, and macOS. The extension will use the correct one automatically when switching OSes.

```json
{
  "vscode_custom_css.imports": [
    "file:///C:/Users/MinhTD/.vscode/custom.css",
    "file:///home/minh711/.vscode/custom.css",
    "file:///Users/minh711/.vscode/custom.css"
  ]
}
```
### For Linux

It will need permission:

```zsh
sudo chown -R $USER:$USER /usr/share/code
```

Then turn the permission back:

```zsh
sudo chown -R root:root /usr/share/code
sudo chmod -R 755 /usr/share/code
```
