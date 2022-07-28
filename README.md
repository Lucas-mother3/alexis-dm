<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="
          https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_white_320.png, 537w
          https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_white_640.png, 1074w,
          https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_white.png, 2148w">
          sizes="(max-width: 640px) 537px,
                 (max-width: 1280px) 1074px,
                 (max-width: 2560px) 2148px">
  <source media="(prefers-color-scheme: light)"
          srcset="
          https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_black_320.png, 537w
          https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_black_640.png, 1074w,
          https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_black.png, 2148w">
          sizes="(max-width: 640px) 537px,
                 (max-width: 1280px) 1074px,
                 (max-width: 1920px) 2148px">
  <img alt="ADM logo, which uses a modified version of the Screen Preferences icon from Haiku OS." src="https://raw.githubusercontent.com/Lucas-mother3/alexis-dm/main/logo/adm_icon_black.png" width="640">
</picture>

# Alexis Desktop Manager 
A handy and minimal script for Termux X11.

## How it works:

It's written in Bourne Again Shell (`Bash`), which is included with most Linux distributions, and compatible with various shells like Z Shell (`zsh`). 

It works by launching either `tigervnc` or makes a session from XServer XSDL. It can also support various window managers and desktop environments due to it's simplicity. 

And it's only 4kb, compared to various desktop managers.

## How to use:

1. Clone this repo
2. Modify `adm` and replace all instances of `My desktop` with your desktop environment/window manager of choice
3. Run `chmod a+x adm`
4. Then open the script with `./adm`

(Optional) 5. Put `adm` in `$PREFIX/usr/local/bin`.

## License

This script is licensed under the GNU General Public License Version 3.0, since MIT License is technically not free.
