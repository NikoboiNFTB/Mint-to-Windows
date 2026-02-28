# Mint-to-Windows

Turning Linux Mint 22.3 into Windows 11 project.

## Steps

1. Change background to the Windows 11 background.

```bash
sudo mkdir -p /usr/share/backgrounds/Win11
cd /usr/share/backgrounds/Win11
sudo wget "https://4kwallpapers.com/images/wallpapers/windows-11-dark-mode-blue-stock-official-3840x2400-5630.jpg"
gsettings set org.cinnamon.desktop.background picture-uri  "file:///usr/share/backgrounds/Win11/windows-11-dark-mode-blue-stock-official-3840x2400-5630.jpg"
