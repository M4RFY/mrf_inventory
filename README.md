## mrf_inventory
- This inventory is for those who don't plan to update their QBCore for now.
- Make sure that your core is version 1.2.5 or below because the new inventory update changes most of the features and will not support versions 1.2.6 or above.
- And for the design inspired by the PS layout and AXFW design...
- No support will be provided

## Dependencies
- [ox_lib](https://github.com/overextended/ox_lib/releases/tag/v3.22.1)
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [qb-target](https://github.com/qbcore-framework/qb-target)
- [interact](https://github.com/darktrovx/interact) - Optional
- [qb-smallresources](https://github.com/qbcore-framework/qb-smallresources) - For logging transfer and other history

## Features
- Stashes
- Vehicle Trunk & Glovebox
- Weapon Attachments
- Shops
- Item Drops
- Decay
- Weapons Repair

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Delete qb-weapons
- Replace the 'mrf_' prefix with your prefix (e.g., 'qb-', 'ps-', 'lj-', etc.)
- Add the following code to your server.cfg/resouces.cfg

## Decay
- ['decay'] = 24.0 - in hours
### Example
```lua
    -- Old Format
    ['sandwich']                       = { ['name'] = 'sandwich', ['label'] = 'Sandwich', ['weight'] = 200, ['type'] = 'item', ['image'] = 'sandwich.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Nice bread for your stomach', ['decay'] = 24.0 },
    -- New Format
    sandwich                     = { name = 'sandwich', label = 'Sandwich', weight = 200, type = 'item', image = 'sandwich.png', unique = false, useable = true, shouldClose = true, description = 'Nice bread for your stomach', decay = 24.0 },
```

## Screenshot
![Inventory](https://r2.fivemanage.com/daUBRfSCPD1ZUJhEpVqPi/inv.png)

## Credits
- [qb-inventory](https://github.com/qbcore-framework/qb-inventory) - For Base Code
- [qb-weapons](https://github.com/DonHulieo/qb-weapons) - For Base Code
- [weight]() - I don't remember the creator. Please reach out to me.

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
