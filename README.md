# Orbital APT Repository

APT package repository for [Orbital](https://github.com/OffskyLab/Orbital), served via GitHub Pages.

## Install

```bash
echo "deb [trusted=yes] https://offskylab.github.io/apt stable main" | sudo tee /etc/apt/sources.list.d/orbital.list
sudo apt update
sudo apt install orbital
```

## Update

```bash
sudo apt update && sudo apt upgrade orbital
```
