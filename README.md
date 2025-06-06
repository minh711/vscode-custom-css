# Custom CSS for customizing VSCode

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
