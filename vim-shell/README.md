# How do I exit vim?

### Description for competitors

I've opened vim and can't exit! Can you help me?

### Description for whitecell

In this challange, the user is stuck in vim. They need to find the flag in /etc/super_secret_flag.txt. Provide FLAG as a `--build-arg`.

### Solution

- The simplest way is the `:e /etc/super_secret_flag.txt` but I doubt anyone would guess the exact path.
- In order to get an interactive shell, you'll need to `set shell=/bin/bash` in /home/ctf/.vimrc then `:sh`. Without this set, the shell is still set to /usr/bin/vim.
