# macOS Dotfiles

This repository contains my personal dotfiles for macOS. The script below can be used to install the relevant packages and applications, change various macOS settings based on my preferences and link dotfiles for customisation.

## Installation

To use these dotfiles on your own macOS system, follow these steps:

1. Install Apple's command-line tools, prerequisites for Git and Homebrew:
```
xcode-select --install
```

2. Clone the repository to your home directory:
```
git clone https://github.com/fraserlove/macos-dotfiles.git ~/.dotfiles
```

3. Change into the `.dotfiles` directory and run `install.sh`:
```
cd ~/.dotfiles
chmod +x install.sh
./install/install.sh
```

This will create symbolic links from the dotfiles in this repository to their corresponding locations in your home directory. It will also install various command-line tools and applications using Homebrew.

4. Restart your terminal application to see the changes take effect.

## Usage

This repository contains dotfiles for various applications and settings, including:

-   Fish shell configuration (`~/.config/`)
-   Alacritty configuration (`~/.alacritty.yml`)
-   Neofetch configuration (`.config/neofetch/config.conf`)
-   Git configuration (`~/.gitconfig`)
-   macOS defaults (`~/.macos`)

Feel free to modify these files to suit your own needs.

## Contributing

If you find a bug or have a suggestion for improvement, please open an issue or pull request on GitHub. Contributions are welcome and appreciated!

