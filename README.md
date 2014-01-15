Font-Awesome-Stylus
===================

> Stylus port for Font-Awesome 4.x, and use icons as your needed.

## Install

```bash
git clone https://github.com/heroicyang/Font-Awesome-Stylus.git /to/your-project/stylus/font-awesome-stylus
```

Import `font-awesome-stylus` in your project and configure fonts path correctly (`$fa-font-path`).

## Usage

```
$fa-font-path = "your fonts path"

@import "font-awesome-stylus"

// icons in the project
.{$fa-css-prefix}-glass
  fa-icon("glass")

.{$fa-css-prefix}-music
  fa-icon("music")

// or import all icons
import-all-icons()
```
