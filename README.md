# dotfiles

All the dotfiles I care about, in no particular order.

![screenshot](https://github.com/LennyHirsch/dotfiles/blob/main/screenshot.png?raw=true)

## Installation/Setup

These instructions aren't exhaustive by far; I haven't got the time to document the process fully at the moment, but will hopefully update with better instructions/documentation soon.

### Eww:

1. Install [Eww Widgets](https://elkowar.github.io/eww/)
2. Once installed, place the `./.config/eww` folder in your `.config` directory (`~/.config` by default).
3. Run `eww daemon` and `eww open roundbar`

Make sure you have the GeistMono Nerd font installed, or replace `font-family` with your preferred font in `./.config/eww/widgets/roundbar/roundbar.scss` on line 6.

### Kitty:

Make sure you have the GeistMono Nerd font and Fantasque Nerd font installed, or replace with your preferred fonts in `./.config/kitty/kitty.conf`

### Neofetch:

Should work out of the box pretty much. Line 17 is hacky because I'm a hack. Delete that and uncomment line 16 if you don't happen to have the exact same CPU.
To run with the oni mask ascii, run `neofetch --ascii ~/.config/neofetch/oni.txt`.

### Neovim:

NVChad with Catppuccin-Mocha theme, and some extra bells and whistles. Theme is included with NVChad, but I've overridden to give more control over specifics like window transparency.
