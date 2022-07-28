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

1. Clone this repo
2. Modify `adm` and replace all instances of `My desktop` with your desktop environment/window manager of choice
3. Run `chmod a+x adm`
4. Then open the script with `./adm`

(Optional) 5. Put `adm` in `/usr/local/bin` or `/data/data/com.termux/files/usr/local/bin`.

## Compatibility with Linux environments in `proot-distro`

### Ubuntu 22.04 LTS (and possibly older versions) 

The xstartup option of `vncserver` will work only if you use the executable of the program, and not it's xstartup file. 
XServer will work however. 

### Termux (with the X11 repo) 

Will work normally with the xstartup file. 
XServer will probably work with the script. 

### Arch Linux

I couldn't figure out how to get vncserver working, so if you have any ideas, please let me know. 
XServer is untested. 

### Untested:

- Alpine Linux
- Debian 
- Fedora
- Manjaro
- OpenSUSE
- Void Linux

## License

This script is licensed under the GNU General Public License Version 3.0, since MIT License is technically not free.

This is free software, so I can fuck off with companies. 
