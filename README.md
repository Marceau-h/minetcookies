# minetcookies

[![PyPI - Version](https://img.shields.io/pypi/v/minetcookies.svg)](https://pypi.org/project/minetcookies)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/minetcookies.svg)](https://pypi.org/project/minetcookies)

-----

**Table of Contents**

- [Installation](#installation)
- [License](#license)
- [Description](#description)
- [Usage](#usage)
  - [Examples](#examples)
    - [Full commands](#full-commands)
    - [Cookies only](#cookies-only)
- [Medias supported](#medias-supported)
- [Browsers supported](#browsers-supported)

## Installation

```bash 
pip install minetcookies
```

## License

`minetcookies` is distributed under the terms of the [AGPLv3 license](https://www.gnu.org/licenses/agpl-3.0.en.html).

# Minet cookies, a cookie manager for Minet

## Description

`minetcookies` is a cookie manager for [Minet](https://github.com/medialab/minet).
It checks for cookies by using the minet cli ant then writes them to the Minet config file.
Preventing you from doing it manually.

Additionally, it can also read minet commands, in that case, it will check for cookies and then return a folder path 
based on the curent directory and the keyword. This is useful for chaining commands.

CAUTION: For this script to work, you need to have one of the supported browsers installed and be logged in to the
social media you want to use minet with.

## Usage

```bash
minetcookies [media]
```
or
```bash
minetcookies [minet command]
```

### Examples

#### Full commands

```bash
minetcookies tiktok search-videos test -l 20
```
OR 
```bash
minet twitter scrape tweets test --limit 20
```

#### Cookies only

```bash
minetcookies [tiktok|twitter|facebook|instagram]
```

## Medias supported

- Instagram
- Tiktok
- Twitter
- Facebook

## Browsers supported

- Chrome
- Firefox
- Chromium
- Edge
