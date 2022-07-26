<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_white_320.png">
  <source media="(prefers-color-scheme: light)"
          srcset="https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_black_320.png">
  <img alt="ADM logo, which uses a modified version of the Screen Preferences icon from Haiku OS." src="https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_black.png" width="320">
</picture>

# Alexis Desktop Manager 
A handy and minimal script for Termux X11.

## How it works:

It's written in Bourne Again Shell (`Bash`), which is included with most Linux distributions, and compatible with various shells like Z Shell (`zsh`). 

It works by launching either `tigervnc` or making a session from XServer XSDL. It can also support various window managers and desktop environments due to it's simplicity. 

And it's only 5kb, compared to various desktop managers.

## How to use:

1. Clone this repo or grab one at the [releases](https://github.com/Lucas-mother3/alexis-dm/releases) tab.
2. Modify `adm` and replace all instances of `My desktop` with your desktop environment/window manager of choice
3. Run `chmod a+x adm`
4. Then open the script with `./adm`

(Optional) 5. Put `adm` in `/usr/local/bin` or `/data/data/com.termux/files/usr/local/bin`.

## Compatibility with Linux environments in `proot-distro`

Now moved to the [wiki](https://github.com/Lucas-mother3/alexis-dm/wiki).

## Contributors
- [@Lucas-mother3](https://github.com/Lucas-mother3): That's me, the creator of the script.
- [@Damaj301damaj-lol](https://github.com/Damaj301damaj-lol): Rewrite the script to case for much smaller file size and lines of code. (60 sloc with rewrite vs 353 sloc without rewrite)

## License

This script is licensed under the GNU General Public License Version 3.0, since MIT License is technically not free.

This is free software, so I can fuck off with companies. 
