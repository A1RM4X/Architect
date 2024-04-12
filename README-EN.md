# 🐧 ARCHITECT SCRIPT

[![fr](https://img.shields.io/badge/langue-français-blue.svg)](https://github.com/Gaming-Linux-FR/Architect/blob/main/README.md)

A post-installation script for Arch Linux, designed to configure a standard Arch system with a minimal set of packages tailored to my needs right after using `archinstall`. Geared towards gaming, this script is intended for a pure Arch Linux experience.

> [!WARNING]
> It was designed based on this [tutorial](https://github.com/Gaming-Linux-FR/tuto-archlinux-fr) which originates from personal note-taking to meet my needs. I can assure you that it works perfectly well on my PC and fully satisfies me. However, **I cannot guarantee the results on your hardware. Use with knowledge of the potential risks, enjoy the script.**

### Archinstall


<img src="https://github.com/Cardiacman13/tuto-archlinux-fr/blob/main/assets/images/LOGO-A1RM4X-2K.png" width="30" height="30"> [ Install Arch like a boss: Archinstall script ](https://youtu.be/56u5tddLxCI?si=0DKyfDp7hQGTfLny)

[![Install Arch like a boss: Archinstall script](https://img.youtube.com/vi/56u5tddLxCI/0.jpg)](https://youtu.be/56u5tddLxCI?si=0DKyfDp7hQGTfLny)

**Installation and usage:**  
To launch `archinstall`, start by updating `archinstall` to ensure you're using the most recent version. This is important because, for example, at the time these lines are written, the Arch Linux ISO version from 01/03/2024 tries to install the "plasma-wayland" package, which has been nonexistent since the release of Plasma 6, leading to an error that crashes archinstall. This issue has been fixed in newer versions of `archinstall`, so updating before starting the installation is essential.

**Update `archinstall`:**
```sh
pacman -Sy archinstall
```

Once `archinstall` is updated, you can launch it with the following command:
```sh
archinstall
```

## Arch Linux Script

```bash
sudo pacman -S --needed git base-devel && git clone https://github.com/Cardiacman13/Architect.git ~/Architect && cd ~/Architect && chmod +x ./architect.sh && ./architect.sh
```

<img src="https://github.com/Cardiacman13/tuto-archlinux-fr/blob/main/assets/images/LOGO-A1RM4X-2K.png" width="30" height="30"> [ Configure Arch the easy way: Architect project by Cardiac ](https://youtu.be/0MV3MxmO7ns?si=eOMc-e4wdSwv1Fbb)

[![Configure Arch the easy way: Architect project by Cardiac](https://img.youtube.com/vi/0MV3MxmO7ns/0.jpg)](https://youtu.be/0MV3MxmO7ns?si=eOMc-e4wdSwv1Fbb)

## Main Features

1. **Configure Package Manager** - Enhance Pacman's functionalities.
2. **Adding Useful Aliases** - Simplify your command-line tasks.
   - `update-arch`: Updates your system apps in one go.
   - `clean-arch`: Removes unused packages.
   - `fix-key`: Solves key-related issues during updates.
   - `update-mirrors`: Refreshes your system's mirror list.
3. **GPU Configuration for Gaming** - Optimal support for AMD, NVIDIA, and Intel drivers
4. **Desktop Environment** - Choose between GNOME, KDE Plasma, XFCE, and i3wm.
5. **Install Base Packages** - Install essential tools, including AUR helpers like `yay` or `paru`.
6. **Miscellaneous Enhancements** - Various adjustments to optimize your Arch experience.
7. **Install Additional Software** - Selection of additional software to customize your installation.

## Troubleshooting

For any questions or problems, feel free to open a discussion in the [discussion section](https://github.com/Cardiacman13/Architect/discussions) of the project.

## Sources

- [ArchWiki](https://wiki.archlinux.org/)
- [GLF Website](https://www.gaminglinux.fr/)
- [GLF Discord](http://discord.gg/EP3Jm8YMvj)
- [Cardiacman's YouTube Channel](https://www.youtube.com/@Cardiacman)

## Acknowledgments

A big thank you to the Arch Linux team, the Arch Linux community, AUR maintainers, contributors, and developers of the packages used in this project. Thanks to the entire GLF Discord community for their tests and feedback.
