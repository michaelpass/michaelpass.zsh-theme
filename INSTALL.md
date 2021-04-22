# Installation
---


This theme is packaged as a ZSH plugin to make it easier to use if you're already using a ZSH framework. If you don't already use a framework, [@unixorn](https://github.com/unixorn) highly recommends [Zgenom](https://github.com/jandamm/zgenom), because it is fast and also supports using [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)'s internal plugins. I personally do all of my plugin management through [Oh My Zsh](https://ohmyz.sh/), and owe its many developers an eternal debt of gratitude.

### Bash / not using a framework

If you're using `bash`, or aren't using a framework, you can either:

* Clone this repository into your home folder and move it directly into your plugins path (assuming Oh My Zsh installed as an example):

```
$ cd # Changes current working directory to $HOME
$ git clone git@github.com:michaelpass/michaelpass.zsh-theme.git # Clones theme source files into $HOME
$ cd ./michaelpass.zsh-theme # Move into newly cloned directory
$ cp michaelpass.zsh-theme $ZSH/plugins
```

### Oh My Zsh
1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone git@github.com:michaelpass/michaelpass.zsh-theme michaelpass`
3. Add michaelpass to your plugin list - edit `~.zshrc` and change `plugins=(...)` to `plugins=(... michaelpass)`

p.s. If you haven't checked out already, please check out Oh My Zsh:
https://ohmyz.sh/
