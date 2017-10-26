# DGI Fontello

## Introduction

This module allows for integration of an exported fontello configuration, once
placed in the 'sites/all/libraries', downloaded from
[Fontello](http://fontello.com/). This module will also integrate fontello
icon exports with the Icons API module in addition to adding the fontello
library to every page.

## Requirements

* [Icon API](https://www.drupal.org/project/icon)
* [Libraries API](https://www.drupal.org/project/libraries)

## Installation

Install as usual, see
[this](https://drupal.org/documentation/install/modules-themes/modules-7) for
further information

## Configuration

Download the desired fontello configuration on the
[Fontello](http://fontello.com/) site, extract the fontello folder to 
'sites/all/libraries' directory, and RENAME the fontello folder to 
'saas_fontello'. The config.json will automatically be parsed and 
iterated on to compile the font names with there associated CSS 
classes.

## Troubleshooting/Issues

Having problems or solved a problem? Contact
[discoverygarden](http://support.discoverygarden.ca).

## Maintainers/Sponsors

Current maintainers:

* [discoverygarden](http://www.discoverygarden.ca)

## Development

If you would like to contribute to this module, please check out our helpful
[Documentation]
(https://github.com/Islandora/islandora/wiki#wiki-documentation-for-developers)
info, [Developers](http://islandora.ca/developers) section on Islandora.ca and
contact [discoverygarden](http://support.discoverygarden.ca).

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
