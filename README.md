# 🐧 ARCHITECT SCRIPT

A minimalist archlinux configuration script

## Table of Contents

<div align = center>

&ensp;[<kbd> <br> All-in-one script <br> </kbd>](#script)&ensp;
&ensp;[<kbd> <br> Tutorial <br> </kbd>](#elevate)&ensp;
&ensp;[<kbd> <br> Gaming <br> </kbd>](#gaming)&ensp;
&ensp;[<kbd> <br> Optimization <br> </kbd>](#optimization)&ensp;
&ensp;[<kbd> <br> Troubleshooting <br> </kbd>](#troubleshooting)&ensp;
&ensp;[<kbd> <br> Community stuff <br> </kbd>](#community)&ensp;
&ensp;[<kbd> <br> Wiki <br> </kbd>](https://github.com/Cardiacman13/Architect/wiki)&ensp;
<br><br><br><br></div>

## 🚀 Arch Linux Script <a name="script"/>

This script is perfect for configuring a **stock Arch** system with a **minimal set of packages** tailored to your needs right after using `archinstall`. Specifically, it's **geared towards gaming**.

> [!IMPORTANT]
> It's specifically designed for a pure Arch Linux experience (not tested on *Garuda*, *Manjaro*, etc.).
> We make all our test based on a fresh install of Arch Linux with [`archinstall`](https://github.com/archlinux/archinstall).
> It is not suitable for outdated computers. Ensure your hardware meets the requirements for the latest Nvidia drivers.

> [!CAUTION]
> The script modifies your system configuration, see the wiki or comunity pannel for more informations.

Execute the following in the terminal to run the script (**requires sudo access**):

```bash
sudo pacman -S git base-devel && git clone https://github.com/Cardiacman13/Architect.git ~/Architect && cd ~/Architect && ./architect.sh
```

## 📝 Main Features

### 1. 🚀 Configure Package Manager
Boost Pacman's functionality:
- 🎨 Enabling colored output.
- 📝 Detailed package lists.
- ⚡ Parallel downloads.
- 🔗 Multilib support.

### 2. ⌨️ Adding Useful Aliases
Ease your command-line tasks:
- `update-arch`: Updates your system apps in one go.
- `clean-arch`: Removes unused packages.
- `fix-key`: Solves key-related issues for updates.
- `update-mirrors`: Refreshes your system's mirror list.

### 3. 🎮 GPU Setup for Gaming (AMD, NVIDIA, Intel)
Prepare your system for gaming with :
- 🎮 GPU drivers choises:
  - 📹 AMD and 32-bit library support.
  - 📹 Intel and 32-bit library support.
  - 🔄 NVIDIA choises:
    - **Nvidia**: Standard drivers **recommended for most**.
    - **Nvidia-all**: For advanced users (via [`Frogging-Family/nvidia-all`](https://github.com/Frogging-Family/nvidia-all) repo).

### 4. 🖥️ Desktop Environment
Choose your DE:
- 🖥️ `GNOME`.
- 🖥️ `KDE Plasma`.
- 🖥️ `XFCE`.
- 🖥️ `i3wm` ([custom config](https://github.com/wmemcpy/i3-config) coming soon... 😏).

### 5. 📦 Install Base Packages
Essential packages for a rounded experience:
- 📦 AUR helpers: [`yay`](https://github.com/Jguer/yay) or [`paru`](https://github.com/Morganamilo/paru).
- 🖋️ Fonts, Emoji.
- 🎬 Codecs.
- ➕ Other crucial packages.

### 6. 🛠️ Miscellaneous Enhancements
Tune-up your system:
- 🎲 Boost `vm.max_map_count` for better Windows game compatibility. [Arch wiki about vm-max-map-count](https://wiki.archlinux.org/title/gaming#Increase_vm.max_map_count)
- 🖨️ Options for Print support.
- 🎵 Bluetooth configuration.
- 🎮 Enhanced support for Xbox, PS5, 8bitdo controllers.
- 🐟 Suggest Fish shell configuration. (zsh in WIP)

### 7. 🔄 Ask to Install Additional Software
Select additional software based on your needs:

| Name                    | Package                                     | Type    |
|-------------------------|---------------------------------------------|---------|
| OBS Studio (from repo)  | obs-studio                                  | package |
| Firefox                 | firefox firefox-i18n-lang                   | package |
| Brave                   | brave-bin                                   | package |
| Chromium                | chromium                                    | package |
| Vivaldi                 | vivaldi                                     | package |
| Google Chrome           | google-chrome                               | package |
| Microsoft Edge          | microsoft-edge-stable-bin                   | package |
| Discord                 | discord                                     | package |
| Steam                   | steam                                       | package |
| Lutris                  | lutris wine-staging                         | package |
| Heroic Games Launcher   | heroic-games-launcher-bin                   | package |
| Goverlay                | goverlay                                    | package |
| protonup-qt             | protonup-qt-bin                             | package |
| Spotify                 | spotify                                     | package |
| Kdenlive                | kdenlive                                    | package |
| Davinci Resolve         | davinci-resolve                             | package |
| Davinci Resolve Studio  | davinci-resolve-studio                      | package |
| LibreOffice             | libreoffice-fresh libreoffice-fresh-lang    | package |
| OnlyOffice              | onlyoffice-bin                              | package |
| Gimp                    | gimp                                        | package |
| Inkscape                | inkscape                                    | package |
| Krita                   | krita                                       | package |
| VLC                     | vlc                                         | package |
| Visual Studio Code      | visual-studio-code-bin                      | package |
| Virtualbox              | virtualbox virtualbox-host-dkms             | package |
| Open RGB                | openrgb-bin                                 | package |
| Arch Update             | arch-update                                 | package |

## Troubleshooting

- For help, visit the GLF Discord (fr/en): [Discord GLF](http://discord.gg/EP3Jm8YMvj)

## Sources

Sources and useful links :
- [ArchWiki](https://wiki.archlinux.org/)
- [Site GLF](https://www.gaminglinux.fr/)
- [GLF Discord](http://discord.gg/EP3Jm8YMvj)
- [My Youtube channel](https://www.youtube.com/@Cardiacman)

## Contribution

Contributions to this project are welcome! If you have suggestions, bug reports, or contributions, please open an issue or a pull request in the repository.

As you can see this project is available in French, English, Spanish, Italian & German. Translators are more than welcome ! :people_holding_hands:

## 🙏 Acknowledgments

- [Arch Linux](https://archlinux.org/) team for their amazing work.
- Arch Linux community for their amazing documentation.
- AUR maintainers for their hard work.
- developers of the packages used in this project. Special mention to : 
- [Frogging Family](https://github.com/Frogging-Family)
- [OpenRGB](https://github.com/CalcProgrammer1/OpenRGB)
- Thanks to the [GLF Discord](https://discord.gg/6t4REDETJd) for the numerous tests and feedback.
- Huge thanks to [wmemcpy](https://github.com/wmemcpy) for all his work on this project.
