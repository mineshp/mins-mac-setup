# Mac Setup Guide

Instructions to follow to setup or migrate over to a new Mac

## Steps

1. Install iTerm2 (replacement for Terminal and iTerm)

2. Setup and configure Zsh on iterm2

Upgrade oh my zsh

```bash
upgrade_oh_my_zsh
```

- Add powerlevel9k theme

```bash
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-mu-zsh/custom/themes/powerlevel9k

ZSH_THEME="powerlevel9k/powerlevel9k"

source ~/.zshrc
```

- Update iTerm2 with powerlevel9k support

```bash
curl -L https://iterm2.com/shell_integration/install_shell_integration_and_utilities.sh | bash
```

3. Install Xcode

```bash
xcode-select --install

sudo xcode-select --reset
```

1. Setup homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)
```

<https://brew.sh/>

2.

3. Install

4. Install Apps

- Chrome
- Firefox for Developer
- Slack Desktop
- Visual Studio Code
- Alfred
- Adobe Reader
- Dropbox
- Docker Hub for Desktop
