# Telegram Era Theme


![Telegram](https://img.shields.io/badge/Telegram-Theme-ba694b?style=flat&logo=telegram&logoColor=f9f8f4)


This repository contains custom themes for Telegram Desktop and iOS, designed to provide a unique and visually appealing experience. The themes are based on a carefully selected color palette and include options for different styles. Additionally, custom wallpapers are provided to complement the themes.

---
## Preview

![image_2025-07-03_23-51-23](https://github.com/user-attachments/assets/61254893-01c2-4854-8bc5-b4114e411da3)

---

## Features

- Dark mode design with a focus on readability and aesthetics
- Custom colors for various UI elements, such as backgrounds, text, buttons, and more
- Two theme versions: MyPalette and MyPaletteV2, with MyPaletteV2 featuring a purple accent color instead of green
- Custom wallpapers in both raster (PNG) and vector (SVG) formats
- Cross-platform support for both desktop and iOS versions

## Project Structure

```
├── EraThemes/
│   └── IOS/
│       └── ios_telegram_theme.txt          # Theme configuration for Telegram on iOS
├── themes/
│   └── desktop/
│       ├── MyPalette.tdesktop-palette      # First version of the desktop theme
│       └── MyPaletteV2.tdesktop-palette    # Second version with purple accents
├── wallpapers/
│   ├── raster/
│   │   ├── chat_wallpaper1.png             # Raster wallpaper 1
│   │   └── chat_wallpaper2.png             # Raster wallpaper 2
│   └── svg/
│       ├── chat_wallpaper1.svg             # Vector wallpaper 1
│       └── chat_wallpaper2.svg             # Vector wallpaper 2
└── README.md                               # This file
```

## Installation

### For Telegram Desktop

1. Choose one of the palette files: `MyPalette.tdesktop-palette` or `MyPaletteV2.tdesktop-palette` from the `themes/desktop` directory
2. Create a new text file and copy the content of the chosen palette file into it
3. Save this text file as `colors.tdesktop-theme`
4. (Optional) Choose a wallpaper from the `wallpapers/raster` or `wallpapers/svg` directory
5. Create a zip archive containing the `colors.tdesktop-theme` file and, if chosen, the wallpaper file
6. Rename the zip archive to have a `.tdesktop-theme` extension, for example, `MyTheme.tdesktop-theme`
7. Open Telegram Desktop, go to Settings > Chat Settings > Browse Themes > Import theme, and select your `.tdesktop-theme` file

**Note:** Telegram Desktop supports JPEG and PNG formats for backgrounds. If using an SVG wallpaper, convert it to a raster format (e.g., PNG) before including it in the zip file.

### For iOS

The `EraThemes/IOS/ios_telegram_theme.txt` file contains a theme configuration for Telegram on iOS. Please refer to Telegram's official documentation for instructions on applying themes on iOS.

## Usage

Once the theme is imported, you can select it from the list of available themes in Telegram Desktop. The theme will provide a cohesive dark interface with carefully chosen colors for optimal readability and visual appeal.

## Wallpapers

The `wallpapers` directory contains custom wallpapers in both raster (PNG) and vector (SVG) formats. The raster images can be used directly as chat backgrounds in Telegram. The SVG files are provided for flexibility and can be converted to raster formats if needed.

## Theme Preview

Here's a snippet from `MyPalette.tdesktop-palette` to give you a sense of the theme's style:

```
// Base colors
bg0_hard: #2a2a28;        // Main background
bg0:      #2f2f2d;        // Slightly lighter background
bg0_soft: #333331;        // Message blocks
fg0:      #f9f8f4;        // Message text (lightest)

// Accent colors
bright_orange:  #ba694b;   // Primary accent
bright_green:   #7a9b6b;   // Success indicators
bright_red:     #d67762;   // Errors/attention
```

For the full theme files, check the `themes/desktop` directory.

---

### Accent Color Palette

| Color         | Badge                                                                                                                 | Hex Code   |
| ------------- | --------------------------------------------------------------------------------------------------------------------- | ---------- |
| 🔶 **Orange** | ![Orange](https://img.shields.io/badge/Accent--Orange-ba694b?style=for-the-badge&logoColor=white&labelColor=2a2a28) | `#ba694b`  |
| 🔷 **Blue**   | ![Blue](https://img.shields.io/badge/Accent--Blue-3d6cac?style=for-the-badge&logoColor=white&labelColor=2a2a28)     | `#3d6cac`  |
| 🔴 **Red**    | ![Red](https://img.shields.io/badge/Accent--Red-d67762?style=for-the-badge&logoColor=white&labelColor=2a2a28)       | `#d67762`  |
| 🟣 **Purple** | ![Purple](https://img.shields.io/badge/Accent--Purple-9b7aa6?style=for-the-badge&logoColor=white&labelColor=2a2a28) | `#9b7aa6`  |
| 🟡 **Yellow** | ![Yellow](https://img.shields.io/badge/Accent--Yellow-c9a96e?style=for-the-badge&logoColor=white&labelColor=2a2a28) | `#c9a96e`  |
| 🟢 **Aqua**   | ![Aqua](https://img.shields.io/badge/Accent--Aqua-6b9b9b?style=for-the-badge&logoColor=white&labelColor=2a2a28)     | `#6b9b9b`  |

---
 

## Contributing

If you have suggestions or improvements, feel free to submit issues or pull requests to this repository.

## License

This project is open-source and available under the MIT License.
