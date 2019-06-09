# Macup

Macup is a script to setup a macOS macup for web, mobile and infrastructure development. It installs apps, dotfiles and configures macOS root configuration settings

## Install

Download the script:

```bash
curl --remote-name https://raw.githubusercontent.com/Bajocode/macup/master/macup 
```

Review the script:

```sh
less macup
```

Execute the downloaded script:

```sh
sh macup 2>&1 | tee ~/macup.log
```

Optionally, review the log:

```sh
less ~/macup.log
```

## Installed components

### Apps
* cask "amethyst"
* cask "virtualbox"
* cask "docker"
* cask "java"
* cask "visual-studio-code"
* cask "webstorm"
* cask "iterm2"
* cask "fastlane"
* cask "spotify"
* cask "google-chrome"
* cask "dropbox"

* ### Tools
* brew "python"
* brew "go"
* brew "cmake"
* brew "zsh"
* brew "tmux"
* brew "jupyter"
* brew "vim"
* brew "kubernetes-cli"
* brew "kubernetes-helm"
