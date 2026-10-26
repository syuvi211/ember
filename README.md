[![AUR](https://img.shields.io/aur/version/ember?logo=arch-linux&label=AUR)](https://aur.archlinux.org/packages/ember)
[![License](https://img.shields.io/badge/license-GPLv3-brightgreen)]()
[![Language](https://img.shields.io/badge/language-Ruby-red)]()

# Ember

**Ember** is a minimal AUR helper written in Ruby. It allows you to easily install, update, search, and remove AUR packages with a simple command-line interface.

## Installation

install **Ember** via the PKGBUILD:




```bash
git clone https://github.com/syuvi211/ember.git
cd ember/
makepkg -si
```

This will build and install Ember


## Usage

Once installed, you can use emb to manage AUR packages.

Update system packages
```bash
ember
```




Install an AUR package
```bash
ember install <package_name>
```


Remove an installed package
```bash
ember remove <package_name>
```

Clean the cache
```bash
ember clean
```
Remove an installed package + config
```bash
ember purge <package_name>
```

Search for AUR packages
```bash
ember search <package>
```

Show help
```bash
ember --help
```

You can also use "emb" instead of "ember"

Ember uses a folder to clone and build AUR packages:
```bash
~/.cache/ember/
```






