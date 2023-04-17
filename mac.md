# Personal macbook settings

## Setup brew
### Install
1. `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
2. `echo 'export PATH=/opt/homebrew/bin:$PATH' >> ~/.zshrc`

- brew install --cask visual-studio-code
- brew install --cask iterm2
- brew install --cask firefox
- brew install --cask unity-hub
- brew install zsh zsh-completions
  - sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  - git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
  - git clone https://github.com/zsh-users/zsh-autosuggestions $ZSH_CUSTOM/plugins/zsh-autosuggestions
  - brew install fasd
- brew install 
- ~~brew install mono~~
  - Recommend to install [here](https://www.mono-project.com/download/stable/). Install from brew isn't include msbuild.
- brew install dotnet
- brew tap homebrew/cask-fonts
- brew install --cask font-fira-code

## iTerm2
- `curl -LO https://raw.githubusercontent.com/mbadolato/iTerm2-Color-Schemes/master/schemes/Dracula.itermcolors`
- Preferences (⌘ + ,)
  - Appearance
    - General
      - Theme: [Minimal]
      - Status bar location: [Bottom]
    - Windows
      - Show line under title bar when the tab bar is not visible [OFF]2
    - Panes
      - Side margins: 12
      - Top & bottom margins: 10
  - Profile
    - Colors
      - and load Color Presets above dracula theme.
    - Text
      - Font size: 15
      - n/n: 110
      - Use ligatures [ON]
      - Unicode normalization form: NFC
    - Session
      - Status bar enabled [ON]
        - Clock, Job Name, git state, CPU Utilization, Memory Utilization
    - Keys
      - Key Mappings
        - Preset - Natural Text Editing
  - Advanced
    - In the Minimal theme, how prominent shoult the tab outline be?: 0
- `git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k`
- `echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>! ~/.zshrc`

My plugins
```
plugins=(
  git
  zsh-syntax-highlighting
  zsh-autosuggestions
  fasd
)
```

## Powerlevel10k
- Use meslo nerd font
- Settings
  - yyyy1111211121n1y

## SSH
- `ssh-keygen`
- `pbcopy < ~/.ssh/id_rsa.pub`

## Git
```
git config --global user.name "Name"
git config --global user.email "me@ydomain.com"
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

### Desktop & Dock
- Show recent application in Dock [OFF]

### Trackpad
- Tab to click [ON]
- Natural Scrolling [OFF]
- Mission Control [Swipe Up with Four Fingers]

### Lock Screen
- Require password after screen saver begins or display is turned off [Immediately]

### Keyboard
- Keyboard navigation [ON]

## Finder
- Settings (⌘ + ,)
  - Advanced
    - Show all filename extensions
