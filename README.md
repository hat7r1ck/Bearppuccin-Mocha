# Bearppuccin-Mocha
## Bear Catppuccin Mocha Theme

A custom **Catppuccin Mocha** theme for Bear, offering a cozy dark experience with rich, vibrant highlights. Since there’s no official documentation on Bear’s internal theme variables, the structure from the default **Catppuccin Latte.theme** file was used. All colors follow the [Catppuccin Style Guide](https://github.com/catppuccin/catppuccin/blob/main/docs/style-guide.md).

> **Note:** Catppuccin is available in four flavors—Latte, Frappe, Macchiato, and Mocha. Currently, **only Mocha** is provided here; there are no plans to create the other three flavors at this time.

---

## Installation (macOS)

1. **Locate Bear’s `Resources` Folder**  
   - Open **Finder** and go to your **Applications** folder.  
   - Right‑click on **Bear** and select **Show Package Contents**.  
   - Navigate to:  
     ```
     Contents → Frameworks → Bear Core Frameworks → Resources
     ```
     
    - Inside `Resources`, look for the default `.theme` files (e.g., `Catppuccin Latte.theme`).

2. **Back Up the Original Theme**  
   - In the `Resources` folder, find the original Bear theme you plan to replace (for example, `Catppuccin Latte.theme`).  
   - Copy it to a safe location outside the Bear app so you can restore it later if needed.

3. **Copy the Custom Theme Contents**  
   - Open `src/Bearppuccin Mocha.json` in a text editor.  
   - **Select all** (Cmd+A) and **copy** (Cmd+C).

4. **Paste into Bear’s Theme File**  
   - Open the original `.theme` file you want to replace, such as `Catppuccin Latte.theme`, in a text editor.  
   - **Select all** and **paste** (Cmd+V) the contents you copied from `Bearppuccin Mocha.json`.  
   - **Save** your changes.
     
   > **Note:** Editing the `.theme` files in Bear’s application folder may require **admin privileges** depending on your macOS permissions.

5. **Restart Bear**  
   - Launch Bear or quit and reopen if it was already running.  
   - In **Preferences → Themes**, select the theme you replaced (e.g., **Catppuccin Latte**).  
   - You should now see your custom Catppuccin Mocha colors in Bear.

---

## Important Notes

- **No Official Bear Theme Docs**  
  Bear does not publicly document which JSON keys or variables it uses for theming. This project started by taking `Catppuccin Latte.theme` as a reference and swapping out color values with Catppuccin Mocha equivalents, following the style guide’s best practices.

- **Overwriting on App Updates**  
  Every Bear update restores the original `.theme` files. Keep your custom `.theme` file backed up outside the Bear app, and simply overwrite the default again after each update.

- **Color Management**  
  Designers and photographers know that color management can be tricky. If you see unexpected shifts, it might be your monitor’s custom ICC profile. Experiment with other hex values from the [Catppuccin Mocha palette](https://catppuccin.com/palette) to suit your preferences.

- **Windows Installation**  
  Bear is officially macOS‑only. If you somehow install or emulate Bear on Windows, feel free to share your process!

---

## Contributing & Sharing

- **Fork** this repository and submit a **Pull Request** if you improve or extend the theme.  
- **Open an Issue** if you have questions, run into problems, or want to share screenshots of your customized Bear.  

Enjoy your new **Catppuccin Mocha** experience in Bear!
