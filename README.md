# Grym
Grym is a bad bitmap extraction and injection tool for Halo 3 PC.

## Usage:
grym.exe -m <path to map to extract from> -i <bitm's zone index>
grym.exe -m <path to map to extract from> -i <bitm's zone index> -n <path to DDS to inject>

## Parameters:
    -m      Map path (If injecting, Grym will copy the map before injecting)
    -i      Zone index of the page you want to extract from/inject to.
    -n      Path to the bitmap you want to inject. Only use when injecting.

##Examples:
Bitmap Extraction for the warthog on Last Resort
grym.exe -m zanzibar.map -i 1360

Bitmap Injection for the warthog on Last Resort
grym.exe -m zanzibar.map -i 1360 -n new_warthog_texture.dds

Thanks to:

Camden for the knowledge drop of how the tag system works

Krevil for info on Halo 3 zone info

For info on the manual process here's some loose info 
https://pastebin.com/3Tv1C3Hh
