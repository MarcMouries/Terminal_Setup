# Marc's Terminal Setup

## Install iTerm2 - macOS Terminal Replacement
https://iterm2.com/

## Install oh-my-zsh 
```shell
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
## Set iTerm2 Color Preset to Solarized
1. Open iTerm 2, open Preferences, click on the "Profiles" icon in the preferences toolbar, 
2. Select the "colors" tab. 
3. Click on the "load presets" and select "import...". 
4. Select the Solaris Light or Dark theme file.

## Set iTerm2 theme 
1. Open iTerm 2 
```shell
nano .zshrc
```
2. Set ZSH_THEME=agnoster
3. exit nano

## Install Patched fonts
https://github.com/powerline/fonts

https://github.com/powerline/fonts/blob/master/SourceCodePro/Source%20Code%20Pro%20for%20Powerline.otf

Open the downloaded font and press "Install Font".

Set this font in iTerm2 (iTerm → Preferences → Profiles → Text → Change Font), best to do this for "Font" and for "Non-ASCII Font".

Restart iTerm2 for all changes to take effect.
