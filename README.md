# Crum
      __
    <(o )___
     ( ._> /  Crum is a slightly better bitmap extraction and injection tool for Halo 3 PC. 
      '---'   Formally known as Grym.

As opposed to Grym, Crum by default runs as tool that will prompt you with info on what you want to do just to make command line tools a bit more friendly for beginners. For people that wanted to automate injection through scripting there's still the option to run this from the command line as detailed below.

## Usage:
    crum.exe -m <path to map to extract from> -i <bitm's zone index>
    crum.exe -m <path to map to extract from> -i <bitm's zone index> -n <path to DDS to inject>

## Parameters:
        -m      Map path (If injecting, Crum will copy the map before injecting)
        -i      Zone index of the page you want to extract from/inject to.
        -n      Path to the bitmap you want to inject. Only use when injecting.
        -h     Help info

## Examples:
Bitmap Extraction for the warthog on Last Resort
crum.exe -m zanzibar.map -i 1360

Bitmap Injection for the warthog on Last Resort
crum.exe -m zanzibar.map -i 1360 -n new_warthog_texture.dds

### Thanks to:

Camden for the knowledge drop of how the tag system works

Krevil for info on Halo 3 zone info

Crum the duck

For info on the manual process here's some loose info 
https://pastebin.com/3Tv1C3Hh
