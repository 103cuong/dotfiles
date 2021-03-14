# dotfiles

[![Hits-of-Code](https://hitsofcode.com/github/thekimcuong/dotfiles-for-linux)](https://hitsofcode.com/view/github/thekimcuong/dotfiles-for-linux)
[![Build Status](https://travis-ci.org/thekimcuong/dotfiles-for-linux.svg?branch=main)](https://travis-ci.org/thekimcuong/dotfiles-for-linux)
[![](https://img.shields.io/github/license/thekimcuong/dotfiles-for-linux.svg)](https://github.com/thekimcuong/dotfiles-for-linux/blob/main/LICENSE.md)

> 💻 dotfiles and 🚀 more (ElementaryOS).

### 🧰 general installation

```sh
yes | /bin/bash -c "$(curl -sSL https://raw.githubusercontent.com/thekimcuong/dotfiles-for-linux/main/install.sh)"
```

### ⚙️ ibus-unikey

```sh
ibus-daemon -drx
sudo apt install -y ibus-unikey
ibus restart
ibus-setup
gsettings set org.gnome.desktop.input-sources sources "[('xkb', 'us'), ('ibus', 'Unikey')]"
```

Add **ibus-daemon -drx** to **startup**

### 🔑 generating a new SSH key

```sh
ssh-keygen -t rsa -b 4096 -C "kimcuong060498@gmail.com"
cat ~/.ssh/id_rsa.pub
```

### 💅 other

- [night-owl-pantheon](https://github.com/kimcuong060498/night-owl-pantheon) - 🌌🦉Night Owl theme for Pantheon terminal.
- [dracula-pantheon](https://github.com/kimcuong060498/dracula-pantheon) - 🧛🏻‍♂️ Dark theme for Pantheon terminal.
- [mediumship](https://github.com/swapagarwal/mediumship) - 📚 Read all Medium stories for free!
- [golangci-lint](https://golangci-lint.run/usage/integrations/)
- [protoc](http://google.github.io/proto-lens/installing-protoc.html)
- [Telegram](https://desktop.telegram.org/)
- [Dockstation](https://dockstation.io/)
- [BloomRPC](https://github.com/uw-labs/bloomrpc)

## 🔖 license

MIT
