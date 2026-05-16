# Theme Name

## Features

## Installation

## Configuration

1. Add favicon.svg to /static in site directory
2. Add logo.png to /static in site directory
3. Customize TOML config file
 
Add navbar links and in toml config

Examples based on current theme configuration:
 
```toml
[[menus.nav]]
name = 'Home'
url = '/'
weight = 1

[[menus.nav]]
identifier = 'about'
name = 'About'
url = '/about'
weight = 2

[[menus.nav]]
name = 'Notes'
url = '/notes'
weight = 20

[[menus.nav]]
name = 'Papers'
url = '/papers'
weight = 30

[[menus.nav]]
name = 'Projects'
url = '/projects'
weight = 30
```