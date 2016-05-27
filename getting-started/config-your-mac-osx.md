# Config your Mac OSX


## Terminal: [iTerm2](http://iterm2.com/) & [oh-my-zsh](http://ohmyz.sh/)

### oh-my-zsh

Install oh-my-zsh via `curl`:

```bash
$ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

[Official Docs](https://github.com/robbyrussell/oh-my-zsh/wiki)

### iTerm2

iTerm2 is a replacement for the terminal app taht ships with OS X.

Download and install iterm2 via [this link](http://iterm2.com)

Why iTerm2?

- Split pane views
- Hotkey window
- Better search highlighting
- Mouseless copy

## Install Node.js

Install Node.js via [this link](http://nodejs.org/).

### NVM

You can [NVM](https://github.com/creationix/nvm)(Node Version Manager) to install node.js. Install it via `wget`:

```bash
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.1/install.sh | bash
```

follow the official docs to use nvm.

## Homebrew

Install homebrew.

## Git

Using homebrew to install git.

```bash
brew install git
```

Git config:

```bash
> git config --global user.name "YOUR_NAME"
> git config --global user.email YOUR_EMAIL
```

## References

1. [知乎：程序员如何优雅使用Mac](https://www.zhihu.com/question/20873070)
2. [A Beautifully Productive Terminal Experience](http://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/)