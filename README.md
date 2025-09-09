# Theme Name

## Features

## Installation

## Configuration

1. Add favicon.svg to /static in site directory
2. Add logo.png to /static in site directory
3. Customize TOML config file
 
Add navbar links and dropdown items in toml config

Examples:
 
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

[[menus.navdropdown]]
name = 'Posts'
url = '/posts'
weight = 20

[[menus.navdropdown]]
name = 'Tags'
url = '/tags'
weight = 30
```