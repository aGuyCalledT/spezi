# Spezi Themes

This repository provides custom themes for **kitty terminal emulator** and **oh my posh** inspired by 'Paulaner Spezi' as such it is based around it's colors, giving it a nice vibrant, warm and deep color palate.

source: [https://www.color-hex.com/color-palette/116051](https://colorhunt.co/palette/f9ed69f08a5db83b5e6a2c70)

---

## Installation
* Make sure you have **git** installed, as well as **oh-my-posh** and **kitty**
* Clone this repository:
```bash
git clone https://github.com/aGuyCalledT/spezi.git
cd spezi
```
- Now copy both files in their respective dir. Usually `spezi.conf` goes into `~/.config/kitty/themes` (not `/kitten-themes`) and `spezi.omp.json` into `~/.poshthemes`
- Search for `Spezi` in `kitty +kitten themes` and activate it
- Set `~/.poshthemes/spezi.omp.json` as your theme in your `~/.config/fish/config.fish` or `~/.bashrc`
    * For bash: `eval "$(oh-my-posh init bash --config ~/.poshthemes/spezi.omp.json)"`
    * For fish: `oh-my-posh init fish --config ~/.poshthemes/spezi.omp.json | source`
