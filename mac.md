# Personal macbook settings

## 1. Install brew
1. `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
2. `echo 'export PATH=/opt/homebrew/bin:$PATH' >> ~/.zshrc`

## 2. Install other tools
- brew install --cask visual-studio-code
- brew install --cask iterm2
- brew install --cask firefox
- brew install --cask unity-hub
= brew install zsh zsh-completions
  - sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  - git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
  - git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
- brew install 
- brew install mono

## iTerm2
- `curl -LO https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Dracula.itermcolors`
- Preferences (⌘ + ,)
  - Appearance
    - Status bar location [Bottom]
      - Clock, Job Name, git state, CPU Utilization, Memory Utilization
  - Profile
    - Colors
      - and load Color Presets above dracula theme.
    - Session
      - Status bar enabled [ON]
    - Keys
      - Key Mappings
        - Preset - Natural Text Editing
- `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k`
- `echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>! ~/.zshrc`

## Powerlevel10k
- Use meslo nerd font
- Settings
  - Pure
  - Original
  - Compact

## SSH
- `ssh-keygen`
- `pbcopy < ~/.ssh/id_rsa.pub`

## Git
```
git config --global user.name "Your Name"
git config --global user.email "you@your-domain.com"
git config --global core.precomposeunicode true
git config --global core.quotepath false
```

## System Settings
### Accessibility
- Trackpad Options
  - Use trackpad for dragging [ON]
  - Dragging style [Three Finger Drag]

### Trackpad
- Tab to click [ON]
- Natural Scrolling [OFF]
- Mission Control [Swipe Up with Four Fingers]

### Lock Screen
- Require password after screen saver begins or display is turned off [Immediately]

### Keyboard
- Keyboard navigation [ON]

## Finder
- (⌘ + ,) Settings
  - Advanced
    - Show all filename extensions
