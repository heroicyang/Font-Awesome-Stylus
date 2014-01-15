Font-Awesome-Stylus
===================

> Stylus port for Font-Awesome 4.x, and use icons as your needed.

## Install

Import `font-awesome.styl` in your project and configure fonts path correctly (`$fa-font-path`).

## Usage

```
$fa-font-path = "your fonts path"

@import "font-awesome"

.{$fa-css-prefix}-glass
  fa-icon("glass")

.{$fa-css-prefix}-music
  fa-icon("music")

// or import all icons
import-all-icons()
```