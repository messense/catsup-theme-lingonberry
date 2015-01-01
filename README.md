Lingonberry
===============

## Overview

A responsive designed theme for [catsup](https://github.com/whtsky/catsup). It's designed by [Anders Norén](http://andersnoren.se/).

## Installation

Requires `catsup` 0.06+.

The easy way using ``catsup install`` :

```bash
cd /path/to/your/blog
catsup install https://github.com/messense/catsup-theme-lingonberry.git
```

The hard way using git manually:

```bash
cd /path/to/your/blog
mkdir themes
cd themes
git clone https://github.com/messense/catsup-theme-lingonberry.git
mv catsup-theme-lingonberry lingonberry
```

## Configuration

Edit your configuration file, change `theme.name` to `lingonberry`.

## Customize

You can customize your theme by changin `theme.vars`

+ Change blog description
```json
{
    "theme": {
        "name": "seven",
        "vars": {
            "description": "description here",
        }
    }
}
```

+ Add links in footer
```json
{
    "theme": {
        "name": "seven",
        "vars": {
            "links": [
                {
                    "name": "catsup",
                    "url": "https://github.com/whtsky/catsup",
                    "description": "Awesome!"
                }
            ]
        }
    }
}
```
