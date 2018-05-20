zfs-completion
=======================
**zfs completion script for [oh-my-zsh].**

[oh-my-zsh]: http://ohmyz.sh/

Preamble
=======================
oh-my-zsh has many complete plugins, such as pip, docker and git.
But I often use zfs in my work, so I try to write a zsh completion script with zfs.

Usages
=======================
not use zfs-completion

![not use](https://github.com/luoxu34/zfs-completion/blob/master/img/not_use_zfs-completion.gif)

use zfs-completion

![use](https://github.com/luoxu34/zfs-completion/blob/master/img/use_zfs-completion.gif)

Installation
=======================

#### [Oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)

1. Clone this repository in oh-my-zsh's plugins directory:

        git clone https://github.com/luoxu34/zfs-completion.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zfs-completion

2. Activate the plugin in `~/.zshrc`:

        plugins=( [plugins...] zfs-completion)

3. Source `~/.zshrc`  to take changes into account:

        source ~/.zshrc
