# Pink Night

[![Build Status](https://www.travis-ci.org/home-assistant-community-themes/template.svg?branch=master)](https://www.travis-ci.org/home-assistant-community-themes/template)
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg)](https://github.com/custom-components/hacs)

Pink Night theme for Home Assistant

## Screenshots

### Overview

![Theme - Overview](https://raw.githubusercontent.com/timpihl/pink_night/master/docs/theme-overviewa.png)

### Map

![Theme - Map](https://raw.githubusercontent.com/timpihl/pink_night/master/docs/theme-mapa.png)

### Logbook

![Theme - Logbook](https://raw.githubusercontent.com/timpihl/pink_night/master/docs/theme-logbooka.png)

### History

![Theme - History](https://raw.githubusercontent.com/timpihl/pink_night/master/docs/theme-historya.png)

### Developer Tools

![Theme - Developer Tools](https://raw.githubusercontent.com/timpihl/pink_night/master/docs/theme-developer-toolsa.png)

### Configuration

![Theme - Configuration](https://raw.githubusercontent.com/timpihl/pink_night/master/docs/theme-configurationa.png)

### Profile

![Theme - Profile](https://raw.githubusercontent.com/timpihl/pink_night/master/docs/theme-profilea.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### HACS

1. Go to the Community Store.
2. Search for `Pink Night`.
3. Navigate to `Pink Night` theme.
4. Press `Install`.
6. Go to services and trigger the `frontend.reload_themes` service.

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/timpihl/pink_night.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/timpihl/pink_night.git
```
