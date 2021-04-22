# Installation


This theme is packaged as a ZSH plugin to make it easier to use if you're already using a ZSH framework. If you don't already use a framework, [@unixorn](https://github.com/unixorn) highly recommends [Zgenom](https://github.com/jandamm/zgenom), because it is fast and also supports using [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)'s internal plugins. I personally do all of my plugin management through [Oh My Zsh](https://ohmyz.sh/), and owe its many developers an eternal debt of gratitude.


### Oh My Zsh
1. `cd` # Move to user $HOME directory (i.e. "~")`
2. `git clone git@github.com:michaelpass/michaelpass.zsh-theme michaelpass`
3. `cd michaelpass` # Move into newly created directory
4. `cp michaelpass-zsh.theme $ZSH/themes` # Copy theme to themes directory
5. Change current theme to `michaelpass`:
    - edit `~.zshrc` and change `ZSH_THEME="..."` to `ZSH_THEME="michaelpass"`
6. `source ~/.zshrc`
8. Happy Hacking!

Note: Simply moving the theme to your ZSH themes folder and changing the current theme to "michaelpass" should work universally, regardless of what Zsh framework you choose.

p.s. If you haven't checked out already, please check out Oh My Zsh:
https://ohmyz.sh/
