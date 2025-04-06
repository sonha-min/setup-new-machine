# Zsh + Oh My Zsh + Dracula Theme

## Installation

### 1. Install Zsh
Ubuntu/Debian:
```bash
sudo apt install zsh
```
MacOS:
```bash
brew install zsh
```

### 2. Install Oh My Zsh
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Plugins
You can add plugins to your ZSH configuration to enhance its functionality. Here are some popular plugins:
- **git**: Provides many useful aliases and functions for Git.
- **zsh-autosuggestions**: Suggests commands as you type based on your command history.
- **zsh-syntax-highlighting**: Provides syntax highlighting for commands as you type.
- **zsh-completions**: Adds additional completion definitions for ZSH.

Clone plugins into `~/.oh-my-zsh/custom/plugins/` directory (`$ZSH_CUSTOM/plugins/`):
```bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

```bash
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
```

Add plugins to `~/.zshrc`
```bash
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```

Reload your zsh configuration:
```bash
source ~/.zshrc
```

### 3. Use Dracula Theme
Clone the Dracula theme repository:
```bash
git clone https://github.com/dracula/iterm.git
```
Activate the theme:
```bash
1. Open iTerm2
2. Go to Preferences > Profiles > Colors tab
3. Click on the "Color Presets..." dropdown
4. Select "Import..."
5. Choose the Dracula.itermcolors file you downloaded
6. Select "Dracula" from the "Color Presets..." dropdown
```
