ansible-pure
============
[![Build Status](https://travis-ci.org/mwilliammyers/ansible-pure.svg)](https://travis-ci.org/mwilliammyers/ansible-pure)

Install & configure the [pure] prompt for [bash], [zsh] & [fish] shells.

Installation
------------

```
ansible-galaxy install mwilliammyers.pure
```

Requirements
------------

None.

Role Variables
--------------

See [default variables].

Dependencies
------------

None.

Example Playbook
----------------

Using all the [default variables]:

```
    - hosts: all
      roles:
         - role: mwilliammyers.pure
```

Notes
-----

__Warning__: This role modifies your default shell configuration file, eg.
`~/.bash_profile`, `~/.zshrc` or `~/.config/fish/config.fish`.

License
-------

GPLv3

Author Information
------------------

[@mwilliammyers]

[@mwilliammyers]: https://github.com/mwilliammyers
[GNU]: http://www.gnu.org/
[OS X]: http://www.apple.com/osx/
[Xcode]: https://developer.apple.com/xcode/
[aura]: https://github.com/aurapm/aura
[bash]: https://www.gnu.org/software/bash/manual/bashref.html
[coreutils]: http://www.gnu.org/software/coreutils/
[default variables]: defaults/main.yml
[dotstrap]: https://github.com/mwilliammyers/dotstrap
[fasd]: https://github.com/clvv/fasd
[files]: files/
[fish]: http://fishshell.com/
[homebrew]: https://github.com/Homebrew/homebrew
[neovim]: https://github.com/neovim/neovim
[pip]: https://github.com/pypa/pip
[pure]: https://github.com/sindresorhus/pure
[speedcola]: https://github.com/mwilliammyers/speedcola
[variables]: vars/main.yml
[yaourt]: https://github.com/archlinuxfr/yaourt
[z]: https://github.com/rupa/z
[zsh]: http://zsh.sourceforge.net
