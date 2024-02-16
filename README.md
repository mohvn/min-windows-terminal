<div align=center>
    <img src="https://raw.githubusercontent.com/mdxv/min-windows-terminal/main/icon.png" width="200" />

# Min Windows Terminal Theme

Min Theme for Windows Terminal.

![preview-dark](https://i.imgur.com/OW40Rmq.png)

![preview-light](https://i.imgur.com/ipFVusf.png)
</div>

## Usage
1. Launch Windows Terminal
2. Open the **Settings** panel (<kbd>Ctrl + ,</kbd>)
3. Select **Open JSON file** at bottom left corner (<kbd>Ctrl + Shift + ,</kbd>)
4. Choose your _theme_ (min-dark, min-light)
5. Copy the contents of _theme_ (example: min-dark.json) into the opened JSON file under **"schemes"**:

```json
{
    "schemes":
    [
        ..min theme
        ..other schemes
    ],
}
```
6. Save and exit
7. In the **Settings** panel under Profiles, select the profile you want to apply the theme to. **Defaults** will apply to all profiles.
8. Select **Appearance**
9. Choose your _theme_ in the **Color scheme** drop down menu
10. Click on **Save**, enjoy!


Based on [Min Theme](https://github.com/miguelsolorio/min-theme) for VSCode
