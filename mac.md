# Personal macbook settings

## Setup brew
### Install
1. `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
2. `echo 'export PATH=/opt/homebrew/bin:$PATH' >> ~/.zshrc`

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
- brew install dotnet

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
  - yyyy1111211121n1y

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

## Sublime Merge
Library/Application Support/Sublime Merge/Packages/Preferences.sublime-settings
```
{
	"font_size": 12,
	"theme": "Merge Dark.sublime-theme",
	"time_format": "24h",
	"ui_scale": 1.3,
	"render_commit_dialog_message_at_top": true,
	"expand_merge_commits_by_default": true,
}
```

## VSCode
### Plugins
- C#
- Gitlens
- Dracula Official [theme]
- Clover [unity support]

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
