# npr

> noraj's PKGBUILDs repository

A personal ArchLinux user repository.

## Usage

```bash
# Clone the repository
git clone https://github.com/noraj/npr && cd npr

# Install with AUR helper
yay -Bi packages/ba-pentest-commons-meta/
pikaur -P packages/ba-pentest-commons-meta/PKGBUILD

# or Install with makepkg
cd packages/ba-pentest-commons-meta
makepkg -sri
```

## Note

This repository is targeted to host PKGBUILDs that can't be stored either on [AUR](https://aur.archlinux.org/) or [BlackArch](https://github.com/BlackArch/blackarch).
