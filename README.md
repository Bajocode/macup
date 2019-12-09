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
