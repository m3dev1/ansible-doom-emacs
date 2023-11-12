# Summary
Doom Emacs is amazing! It can be a little challenging to get it installed just the right way though. This playbook aims to resolve that.

- Installs Doom Emacs following steps from the official [Doom Emacs repo](https://github.com/doomemacs/doomemacs#install).
- Installs "all-the-icons" and "all-the-icons-fonts" packages and then runs `doom sync`.
- This playbook was designed ot be OS-agnostic so it should work on Linux, macOS, and Windows.

# TODO
- [x] OS-agnostic, no specific OS dependencies.
- [ ] Add customized config.el, init.el, packages.el files.
- [ ] Support version number as variable.
- [ ] Configure encrypted variables.
- [ ] Convert to roles.
