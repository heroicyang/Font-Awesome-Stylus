Font-Awesome-Stylus
===================

> Stylus port for Font-Awesome 4.x, and use icons as your needed.

## Getting Started

**Require Stylus `~0.39.0`**

### Git Submodule

```bash
git submodule add https://github.com/heroicyang/Font-Awesome-Stylus.git /project/styl/font-awesome-stylus
```
### Download

Or [download](https://github.com/heroicyang/Font-Awesome-Stylus/archive/master.zip) and copy to your project.

### Initialization

Import `font-awesome-stylus` in your project and configure fonts path correctly (`$fa-font-path`).

## Usage

```
@import "font-awesome-stylus"

$fa-font-path = "your fonts path"

// icons in the project
.{$fa-css-prefix}-glass
  fa-icon("glass")

.{$fa-css-prefix}-music
  fa-icon("music")

// or import all icons
import-all-icons()
```
