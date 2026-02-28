# Mint-to-Windows

Turning Linux Mint 22.3 into Windows 11 project.

## Steps

1. Change background to the Windows 11 background.

```bash
sudo mkdir -p /usr/share/backgrounds/Win11
cd /usr/share/backgrounds/Win11
sudo wget "https://4kwallpapers.com/images/wallpapers/windows-11-dark-mode-blue-stock-official-3840x2400-5630.jpg"
# Manually set wallpaper to this.
```

2. Get and activate Windows 11 icon pack.

```bash
mkdir -p ~/GitHub/yeyushengfan258/Win11-icon-theme
cd ~/GitHub/yeyushengfan258/Win11-icon-theme
git clone "https://github.com/yeyushengfan258/Win11-icon-theme" .
bash install.sh
# Manually set the icon pack to Win11 in Settings -> Themes -> (Advanced Settings...) -> Icons -> Win11
```

3. Change the panel to look more like the taskbar.

```bash
sudo mkdir -p /usr/share/icons/Win11
cd /usr/share/icons/Win11
sudo wget "https://i.namu.wiki/i/xmwIVu64qlhCyWmBQKaZQMuXqyziycMqKWKVHqo8CsmJYCc4vc2lNc5hVIFfdPSx_7uuIH1FfYb8JTLuJJPzw6pD9E30vXXxlJQ5y5KoR9fzd5-EoM2USnerTKCWMmLcb7o6S20AHNfJs2cD0cHK7A.svg"
# Manually set the Menu icon to this by Right click the Menu -> Configure... -> Icon
```
