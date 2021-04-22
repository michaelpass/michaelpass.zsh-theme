# Installation


This theme is packaged as a Zsh theme to make it easier to use if you're already using a Zsh framework. If you don't already use a framework, [@unixorn](https://github.com/unixorn) highly recommends [Zgenom](https://github.com/jandamm/zgenom), because it is fast and also supports using [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)'s internal plugins/themes. I personally do all of my plugin/theme management through [Oh My Zsh](https://ohmyz.sh/), an thus owe its many developers an eternal debt of gratitude.


### Oh My Zsh
1. Move to user $HOME directory (i.e. "~"):
    `cd`
2. Download michaelpass theme from GitHub:
    `git clone git@github.com:michaelpass/michaelpass.zsh-theme michaelpass`
3. Move into newly created directory
    `cd michaelpass` 
4. Copy theme to Zsh/Oh My Zsh themes directory
    `cp michaelpass-zsh.theme $ZSH/themes` # 
5. Edit current theme to `michaelpass`:
    Open `~/.zshrc` and change `ZSH_THEME="..."` to `ZSH_THEME="michaelpass"`. Save.`
6. Reload Zsh config file:
    `source ~/.zshrc`
7. Happy Hacking! 🎉


### POSIX-compliance

Note: Simply moving the theme to your ZSH themes folder and changing the current theme to "michaelpass" should work universally, regardless of what Zsh framework you choose.

p.s. If you haven't checked out already, please check out Oh My Zsh:
https://ohmyz.sh/
