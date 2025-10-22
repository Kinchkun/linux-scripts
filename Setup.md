# Setup

1. Install basic tooling

```bash
sudo pacman -S rustup cargo-update mise zellij nushell htop git
```

2. Setup SSH

Enable SSH Forwarding. One the Local Machine:


```
Host <NEW HOST>
    ForwardAgent yes
```

Test on remote machine:

```bash
ssh -T git@github.com
```


3. Setup Nvim

```bash
mkdir -p ~/.config
git clone git@github.com:Kinchkun/kickstart.nvim.git ~/.config/nvim
```

4. Change Shell to Nu

```bash
chsh
```
