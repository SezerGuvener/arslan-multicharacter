# QBCore Multiple Characters Script Edited by Qaisenix

# qb-multicharacter
Multi Character Feature for QB-Core Framework :people_holding_hands:

## Video
- Göze hitap eden, estetik bir CSS tasarımıyla özelleştirilmiş ve Türkçeleştirilmiş orijinal QB-Core multicharacter scripti.
[Priview](https://streamable.com/jevw3a)

- Added support for setting default number of characters per player per Rockstar license

# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>


## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [arslan-spawn](https://github.com/SezerGuvener/arslan-spawn) - Spawn selector
- [qb-apartments](https://github.com/qbcore-framework/qb-apartments) - For giving the player a apartment after creating a character.
- [illenium-appearance](https://github.com/SezerGuvener/illenium-appearance) - For the character creation and saving outfits.
- [qb-weathersync](https://github.com/qbcore-framework/qb-weathersync) - For adjusting the weather while player is creating a character.

## Features
- Ability to create up to 5 characters and delete any character.
- Ability to see character information during selection.

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resouces.cfg
```
ensure qb-core
ensure arslan-multicharacter
ensure arslan-spawn
ensure arslan-appearence
ensure qb-apartments
ensure qb-weathersync
```
