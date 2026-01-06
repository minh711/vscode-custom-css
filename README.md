# Custom CSS for customizing VSCode

<img width="1612" height="892" alt="image" src="https://github.com/user-attachments/assets/4b21280f-bbec-441d-9835-b1260d121b20" />

## Features

1. Border for each file on workspace.
2. Border for explorer panel.
3. Border on focused file's tab.
4. ***Change VSCode UI font.***

<img width="466" height="142" alt="image" src="https://github.com/user-attachments/assets/640ab4c0-42af-4a86-9e87-d9d1d6c295bb" />

## Installation

I used this extension:

![image](https://github.com/user-attachments/assets/39561cf5-2e6a-4009-a1b9-dd5639f92c6c)

After that, put the `custom.css` file in the right directory and change it in `settings.json`:

> I have one directory for **Windows** and one for **Linux** (Ubuntu).

```json
{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{usename}/.vscode/custom.css",
    "file:///home/{username}/.vscode/custom.css"
  ],
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
