# Personal macbook settings

## 1. Install brew
1. `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
2. `echo 'export PATH=/opt/homebrew/bin:$PATH' >> ~/.zshrc`

## 2. Install other tools
- brew install --cask visual-studio-code
- brew install --cask iterm2
- brew install zsh
  - sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
- brew install 
- brew install mono

## iTerm2
- `curl -LO https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Dracula.itermcolors`
- (⌘ + ,) Profile-Colors and load Color Presets above dracula theme.
- `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k`
- `echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>! ~/.zshrc`

## Powerlevel10k
- Use meslo nerd font
- Settings
  - Pure
  - Original
  - Compact

## System Settings
### Trackpad
- Tab to click [ON]
- Natural Scrolling [OFF]
- Mission Control [Swipe Up with Four Fingers]
