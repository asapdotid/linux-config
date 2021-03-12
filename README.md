# Custom config for support bash or zsh :computer:

1. Aliasas
1. Function

Clone this repository to `user configuration` directory to your home directory: `$HOME/.config`

```bash
# Install configs
$ git clone https://github.com/asapdotid/linux-config.git "${HOME}"/.config/asaplinux
```

Add script to load `functions` and `aliases` to ZSH or BASH config `(.zshrc or bashrc)` on the bottom.

```bash
source $HOME/.config/asaplinux/aliases
source $HOME/.config/asaplinux/functions
```

## Note:

> Change your environment variables config on `.env`

example:

```bash
EDITOR='vim'
```

Refrence :

- [Emoji Log](https://github.com/ahmadawais/Emoji-Log)

If any issue please contact me [@asapdotid](mailto:asapdotid@gmail.com) :point_left:
