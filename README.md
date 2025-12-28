# 🌊 Kanagawa Custom - Oh My Posh Theme

> "An elegant, serenity-focused terminal theme inspired by the colors of the famous painting *The Great Wave off Kanagawa*."

This is a custom configuration for [Oh My Posh](https://ohmyposh.dev/), designed for developers who prioritize visual comfort and essential information. It replaces the harsh contrast of standard themes with the soothing, desaturated palette of the Kanagawa color scheme.

<img width="1455" height="253" alt="image" src="https://github.com/user-attachments/assets/922466b5-4449-4959-8da6-5dea972db028" />


## ✨ Features

* **🎨 Kanagawa Palette:** Uses specific hex codes like *Old White* (`#DCD7BA`), *Crystal Blue* (`#7E9CD8`), and *Sakura Pink* (`#D27E99`) to reduce eye strain.
* **🧠 RAM Monitor:** Replaces the day-of-week indicator with a live **Memory Usage** tracker (Used/Total GB), perfect for monitoring resource-heavy compilations (C++, Rust, etc).
* **⚡ minimal Git Status:** Clean Git integration showing branch name and sync status without visual clutter.
* **⏱️ Execution Time:** Highlights how long a command took to run (in *Surimi Gold*).
* **📂 Two-Line Prompt:** Separates the path and the command input for better readability on long directory paths.
* **📦 Tech Detection:** Automatically detects and displays Node.js version when valid files are present.

## 🛠️ Requirements

1.  **Windows Terminal** (Recommended) or any modern terminal emulator.
2.  **Oh My Posh** installed on your system.
3.  **Nerd Font** installed (Recommended: `JetBrainsMono Nerd Font`).

## 🚀 Installation

1.  **Download the Theme:**
    Save the `kanagawa.json` file to your preferred location (e.g., `~/.poshthemes/kanagawa.json`).

2.  **Update PowerShell Profile:**
    Open your PowerShell profile:
    ```powershell
    notepad $PROFILE
    ```
    Add or modify the initialization line:
    ```powershell
    oh-my-posh init pwsh --config "C:\Path\To\Your\kanagawa.json" | Invoke-Expression
    ```

3.  **Reload Profile:**
    ```powershell
    . $PROFILE
    ```

## ⚙️ Recommended Terminal Settings

To get the full immersive experience (removing the grey borders), apply these color settings to your **Windows Terminal** `settings.json`:

```json
{
    "name": "Kanagawa",
    "background": "#1f1f28",
    "foreground": "#dcd7ba",
    "cursorColor": "#c8c093",
    "selectionBackground": "#2d4f67",
    "black": "#090618",
    "blue": "#7e9cd8",
    "cyan": "#7fb4ca",
    "green": "#76946a",
    "purple": "#957fb8",
    "red": "#c34043",
    "white": "#c8c093",
    "yellow": "#c0a36e",
    "brightBlack": "#727169",
    "brightBlue": "#7e9cd8",
    "brightCyan": "#7fb4ca",
    "brightGreen": "#98bb6c",
    "brightPurple": "#938aa9",
    "brightRed": "#e82424",
    "brightWhite": "#dcd7ba",
    "brightYellow": "#e6c384"
}
```

## 🎨 Color Palette Reference

| Element | Color Name | Hex |
| :--- | :--- | :--- |
| **Background** | Sumi Ink | `#1f1f28` |
| **Foreground** | Old White | `#DCD7BA` |
| **Git Branch** | Sakura Pink | `#D27E99` |
| **Folder Path** | Crystal Blue | `#7E9CD8` |
| **RAM Icon** | Spring Green | `#76946A` |
| **Exec Time** | Surimi Gold | `#E6C384` |
| **Error** | Samurai Red | `#C34043` |
