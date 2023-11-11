# Summary
- Downloads and installs Nerd Fonts from GitHub repo.
- Currently only the hack nerd font is supported by this playbook.

Equivalent to running the following commands:

```sh
mkdir -p $HOME/.fonts

cd $HOME/.fonts

wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/Hack.tar.xz

tar xJf Hack.tar.xz
```

# TODO
- [x] Support Hack font
- [ ] Make version number a variable
- [ ] Convert to roles
