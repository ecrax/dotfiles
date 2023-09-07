# Dependencies

Window Manager
```zsh
  yay -S hyperland-git
```

Other
```zsh
  yay -S rofi dunst waybar-hyprland-git kitty swaybg swaylock-effects swayidle pamixer light
```

Screenshots
```
  yay -S grim swappy slurp
```

Necessary Font:
- [JetBrains Mono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.2.2/JetBrainsMono.zip)
- [Mononoki Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.2.2/Mononoki.zip)

Optional Font:

- [Iosevka Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.2.2/Iosevka.zip)
- [NotoColorEmoji](https://github.com/googlefonts/noto-emoji/raw/main/fonts/NotoColorEmoji.ttf)
- [Codicon](https://github.com/microsoft/vscode-codicons/raw/main/dist/codicon.ttf)
- [Satoshi](https://api.fontshare.com/v2/fonts/download/satoshi)

Once you download them and unpack them, place them into ~/.fonts or ~/.local/share/fonts.

Then run this command for your system to detect the newly installed fonts.

```
fc-cache -fv
```
# Projects Tree
```
~/projects
├── forks       # for GitHub fork
├── uni         # for uni projects
├── playground  # for short-term experiments
└── repos       # for long-term projects
```
