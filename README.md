# base16-tomorrow-schemes

Base16 implementation of Chris Kempson's Tomorrow Themes
https://github.com/clach04/tomorrow-theme/

Difficult to find a concrete reference copy of the Tomorrow colors,
themes seem to have slightly different values :-(
Including images versus theme values.

For example, color picker for sample images from
https://github.com/chriskempson/tomorrow-theme

Tomorrow-Night-Blue-Palette.png
Tomorrow-Night-Bright-Palette.png
Tomorrow-Night-Eighties-Palette.png
Tomorrow-Night-Palette.png
Tomorrow-Palette.png

Differ to various theme files. Also see https://github.com/stonebuddha/base16-chinoiserie-scheme

Also mapping Tomorrow to Base16 (or Base24) is going to vary as Tomorrow only defines 12 colors, not the 16 that Base16 does.

TODO:

  * base24 versions, for decent terminal support (rather than the effectively 8-color support base16 provides to terminals)

## Image Extracts

Values extracted from PNGs.

Color pickers:

  * https://pinetools.com/image-color-picker
  * https://imagecolorpicker.com/

online color viewers:

  * https://www.colorhexa.com/

### chriskempson/tomorrow-theme

Upstream / Original theme
https://github.com/chriskempson/tomorrow-theme/blob/master/Images/Tomorrow-Palette.png

#### Tomorrow

AKA Tomorrow Day

![Tomorrow](https://github.com/ChrisKempson/Tomorrow-Theme/raw/master/Images/Tomorrow-Palette.png)

https://github.com/chriskempson/tomorrow-theme/blob/master/Images/Tomorrow-Palette.png

  * `#ffffff` Background
  * `#f2f2f2` Current Line
  * `#dedede` Selection
  * `#60605f` Foreground
  * `#9fa19e` Comment
  * `#d43e36` Red
  * `#f99927` Orange
  * `#efc200` Yellow
  * `#839b00` Green
  * `#4ba8af` Aqua
  * `#5286bc` Blue
  * `#9c71b7` Purple

#### Tomorrow Night

![Tomorrow Night](https://github.com/ChrisKempson/Tomorrow-Theme/raw/master/Images/Tomorrow-Night-Palette.png)

https://github.com/chriskempson/tomorrow-theme/blob/master/Images/Tomorrow-Night-Palette.png

  * `#27292c` Background
  * `#35383c` Current Line
  * `#474c52` Selection
  * `#d7dad8` Foreground
  * `#a7a8a7` Comment
  * `#d77c79` Red
  * `#e6a472` Orange
  * `#f4cf86` Yellow
  * `#c2c77b` Green
  * `#9ac9c4` Aqua
  * `#92b2ca` Blue
  * `#c0a7c7` Purple

#### Tomorrow Night Blue

![Tomorrow Night Blue](https://github.com/ChrisKempson/Tomorrow-Theme/raw/master/Images/Tomorrow-Night-Blue-Palette.png)

https://github.com/chriskempson/tomorrow-theme/blob/master/Images/Tomorrow-Night-Blue-Palette.png

  * `#003264` Background
  * `#00549f` Selection
  * `#004681` Current Line
  * `#ffffff` Foreground
  * `#8598c4` Comment
  * `#ffafb3` Red
  * `#ffcfa0` Orange
  * `#fff0bb` Yellow
  * `#d9f2b7` Green
  * `#a6feff` Aqua
  * `#c6e2ff` Blue
  * `#f0caff` Purple

#### Tomorrow Night Bright

![Tomorrow Night Bright](https://github.com/ChrisKempson/Tomorrow-Theme/raw/master/Images/Tomorrow-Night-Bright-Palette.png)

https://github.com/chriskempson/tomorrow-theme/blob/master/Images/Tomorrow-Night-Bright-Palette.png

  * `#000000` Background
  * `#373737` Current Line
  * `#545454` Selection
  * `#eeeeee` Foreground
  * `#a7a8a7` Comment
  * `#df6565` Red
  * `#ed9e56` Orange
  * `#ecce58` Yellow
  * `#c5d15c` Green
  * `#80cabf` Aqua
  * `#8cb6e1` Blue
  * `#cfabdf` Purple

#### Tomorrow Night Eighties

![Tomorrow Night Eighties](https://github.com/ChrisKempson/Tomorrow-Theme/raw/master/Images/Tomorrow-Night-Eighties-Palette.png)

https://github.com/chriskempson/tomorrow-theme/blob/master/Images/Tomorrow-Night-Eighties-Palette.png

  * `#3b3b3b` Background
  * `#494949` Current Line
  * `#646464` Selection
  * `#d5d5d5` Foreground
  * `#a9a9a9` Comment
  * `#f78d8c` Red
  * `#fca369` Orange
  * `#ffd479` Yellow
  * `#a8d3a9` Green
  * `#76d4d6` Aqua
  * `#78aad6` Blue
  * `#d6acd6` Purple

### Alex Mirrington Images

Has a tool to generate bar images (similar to https://github.com/clach04/base16-rainbow-generator)
and has a Tomorrow (Day) image.

https://github.com/alexmirrington/base16-spectrum-generator/

#### Tomorrow

![alexmirrington Tomorrow Bright/Bold](https://github.com/alexmirrington/base16-spectrum-generator/blob/master/png/tomorrow.png)

https://github.com/alexmirrington/base16-spectrum-generator/blob/master/png/tomorrow.png

Note this is much brighter than Chris Kempson Tomorrow Day, it makes original look like Eighties / Pastel.

Base16

    base00: "ffffff" # Background
    base01: "e0e0e0" # ? Current Line - potentially
    base02: "d6d6d6" # ? Selection - potentially
    base03: "8e908c" # ? Comment - potentially
    base04: "969896" # ? Comment - potentially most likely
    base05: "4d4d4c" # Most likely Foreground?
    base06: "282a2e" # ? Foreground - potentially
    base07: "1d1f21" # ? Foreground - potentially

    base08: "c82829" # Red
    base09: "f5871f" # Orange
    base0a: "eab700" # Yellow
    base0b: "718c00" # Green
    base0c: "3e999f" # Aqua
    base0d: "4271ae" # Blue
    base0e: "8959a8" # Purple
    base0f: "a3685a" # IndianRed - Some sort of brown?

Tomorrow:

  * `#ffffff` Background
  * `#e0e0e0` Current Line - TODO review
  * `#d6d6d6` Selection - TODO review
  * `#4d4d4c` Foreground - TODO review
  * `#969896` Comment - TODO review
  * `#c82829` Red
  * `#f5871f` Orange
  * `#eab700` Yellow
  * `#718c00` Green
  * `#3e999f` Aqua
  * `#4271ae` Blue
  * `#8959a8` Purple

### James Cherti vim scheme

From https://github.com/jamescherti/vim-tomorrow-night-deepblue

#### Tomorrow Night Deepblue

Extracted from vim color scheme
https://github.com/jamescherti/vim-tomorrow-night-deepblue/blob/master/colors/tomorrow-night-deepblue.vim

  * `#00006f` Background
  * `#00008a` Current Line
  * `#003f8e` Selection
  * `#ffffff` Foreground
  * `#7285b7` Comment
  * `#ff9da4` Red
  * `#ffc58f` Orange
  * `#ffeead` Yellow
  * `#d1f1a9` Green
  * `#99ffff` Aqua
  * `#bbdaff` Blue
  * `#ebbbff` Purple

Potentiall useful (for Base16):

    let s:window = '4d5057'
    let s:darker_background = '00005f'
    let s:cursorline = '082572'

## Template

  * `#RRGGBB` Background
  * `#RRGGBB` Current Line
  * `#RRGGBB` Selection
  * `#RRGGBB` Foreground
  * `#RRGGBB` Comment
  * `#RRGGBB` Red
  * `#RRGGBB` Orange
  * `#RRGGBB` Yellow
  * `#RRGGBB` Green
  * `#RRGGBB` Aqua
  * `#RRGGBB` Blue
  * `#RRGGBB` Purple

## Base16

Based on an extract from https://github.com/chriskempson/base16/blob/main/styling.md

  * Colours `base00` to `base07` are typically variations of a shade and run from darkest to lightest.
  * These colours are used for foreground and background, status bars, line highlighting and such.
  * Colours `base08` to `base0F` are typically individual colours used for types, operators, names and variables.
  * Dark versus light themes
      * For a dark theme,  colours `base00` to `base07` should span from **dark** to **light**.
      * For a light theme, colours `base00` to `base07` should span from **light** to **dark**.

### Base16 Shades

- **base00** - Default Background
- **base01** - Lighter Background (Used for status bars, line number and folding marks)
- **base02** - Selection Background
- **base03** - Comments, Invisibles, Line Highlighting
- **base04** - Dark Foreground (Used for status bars)
- **base05** - Default Foreground, Caret, Delimiters, Operators
- **base06** - Light Foreground (Not often used)
- **base07** - Light Background (Not often used)

### Base16 Colors

- **base08** - Variables, XML Tags, Markup Link Text, Markup Lists, Diff Deleted
- **base09** - Integers, Boolean, Constants, XML Attributes, Markup Link Url
- **base0A** - Classes, Markup Bold, Search Text Background
- **base0B** - Strings, Inherited Class, Markup Code, Diff Inserted
- **base0C** - Support, Regular Expressions, Escape Characters, Markup Quotes
- **base0D** - Functions, Methods, Attribute IDs, Headings
- **base0E** - Keywords, Storage, Selector, Markup Italic, Diff Changed
- **base0F** - Deprecated, Opening/Closing Embedded Language Tags, e.g. `<?php ?>`

### Base16 Color Schemes

  * TODO yaml file for all Tomorrow schemes above
  * tomorrow-night.yaml
  * tomorrow.yaml
  * tomorrow_20120906.yaml
  * vim_tomorrow-night-eighties.yaml
  * vim_tomorrow-night.yaml
  * vim_tomorrow.yaml

For each scheme, generate a preview.
For example using https://github.com/clach04/base16-rainbow-generator
