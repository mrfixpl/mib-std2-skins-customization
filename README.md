# MIB STD2 Skins Customization
Assets ready for MIB2 STD skin customization

⚠️ This is not ready yet!

![Offroad Display with red scales](https://raw.githubusercontent.com/mrfixpl/mib-std2-skins-customization/main/previews/SCREENSHOT_CarMainOffroad_redScales.jpg)

## How to use
* Check if your unit is running one of the supported SW Trains. Update firmware if required. If you don't do it, you need to manually check file names to confirm that you are replacing the right thing
* Enable developer mode in module 5F.
* Download MIB STD2 Toolbox - https://github.com/olli991/mib-std2-pq-zr-toolbox/releases.
* Dump stock skins from unit - use MIB STD2 Toolbox, FTP access, or eMMC memory dump.
* Use `mib-std2-pq-zr-toolbox/tools/extract-mcf.py` script to extract `mcf` assets.
* Replace assets with custom ones.
* Use `mib-std2-pq-zr-toolbox/tools/compress-mcf.py` script to compress assets back to `mcf` format.
* Upload modified skins back to main unit.
* Reboot unit.
* Enter hidden menu, switch to new skin, exit menu.

## Available changes
### `MST2_EU_VW_ZR_P0245T`
#### `skin1`
* `menu_appleIcons`
* `menu_seatIcons`
* `menu_whiteTiles`
* `offroadDisplay_redScales`
* `offroadDisplay_slickWheel`
* `standbyClock_mickey`

### `MST2_EU_VW_ZR_P0480T`
#### `skin5`
* `offroadDisplay_slickWheel`
