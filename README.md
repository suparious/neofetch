<h3 align="center"><img src="https://i.imgur.com/ZQI2EYz.png" alt="logo" height="100px"></h3>
<p align="center">A command-line system information tool written in bash 3.2+</p>

<p align="center">
<a href="./LICENSE.md"><img src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
<a href="https://github.com/Suparious/neofetch/releases"><img src="https://img.shields.io/github/release/Suparious/neofetch.svg"></a>
<a href="https://repology.org/metapackage/neofetch"><img src="https://repology.org/badge/tiny-repos/neofetch.svg" alt="Packaging status"></a>
</p>

---

> **This is an actively maintained fork of [dylanaraps/neofetch](https://github.com/dylanaraps/neofetch).**
>
> The original repository was archived in April 2024. This fork aims to continue development, accept contributions, and keep neofetch alive for the community.
>
> *Thank you, Dylan, for creating this beloved tool.*

---

<img src="https://i.imgur.com/GFmC5Ad.png" alt="neofetch" align="right" height="240px">

Neofetch is a command-line system information tool written in `bash 3.2+`. Neofetch displays information about your operating system, software and hardware in an aesthetic and visually pleasing way.

The overall purpose of Neofetch is to be used in screen-shots of your system. Neofetch shows the information other people want to see. There are other tools available for proper system statistic/diagnostics.

The information by default is displayed alongside your operating system's logo. You can further configure Neofetch to instead use an image, a custom ASCII file, your wallpaper or nothing at all.

<img src="https://i.imgur.com/lUrkQBN.png" alt="neofetch" align="right" height="240px">

You can further configure Neofetch to display exactly what you want it to. Through the use of command-line flags and the configuration file you can change existing information outputs or add your own custom ones.

Neofetch supports almost 150 different operating systems. From Linux to Windows, all the way to more obscure operating systems like Minix, AIX and Haiku. If your favourite operating system is unsupported: Open up an issue and support will be added.


### More: \[[Dependencies](https://github.com/Suparious/neofetch/wiki/Dependencies)\] \[[Installation](https://github.com/Suparious/neofetch/wiki/Installation)\] \[[Wiki](https://github.com/Suparious/neofetch/wiki)\]

## Installation

### Homebrew (macOS/Linux)

```bash
brew tap suparious/suparious
brew install neofetch
```

### From source

```bash
# Clone the repository
git clone https://github.com/Suparious/neofetch.git
cd neofetch

# Install (requires root/sudo)
sudo make install

# Or install to a custom prefix
make PREFIX=~/.local install
```

### Package managers

Many package managers still have neofetch available, though they may have older versions. For the latest updates from this fork, use the Homebrew tap or install from source.

## Upgrading

### Check your current version

```bash
neofetch --version
```

### Homebrew

```bash
# Update the tap and upgrade
brew update
brew upgrade neofetch

# Or install the latest from git (bleeding edge)
brew reinstall --HEAD neofetch
```

### From source

```bash
cd neofetch
git pull
sudo make install
```

## Contributing

Contributions are welcome! This fork is open to:

- Bug fixes
- New OS/distro support
- Feature improvements
- Documentation updates

Please open an issue first to discuss major changes.

## Acknowledgments

- **[Dylan Araps](https://github.com/dylanaraps)** - Original creator of neofetch and many other beloved projects
- All the contributors to the original project
- The community that made neofetch one of the most recognized CLI tools

## License

MIT License - see [LICENSE.md](LICENSE.md)
