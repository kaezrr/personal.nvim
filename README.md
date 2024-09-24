### Install Kickstart

```sh
git clone https://github.com/kaezrr/personal.nvim.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
#### Windows Install
<details><summary>WSL (Windows Subsystem for Linux)</summary>

```
wsl --install
wsl
sudo add-apt-repository ppa:neovim-ppa/unstable -y
sudo apt update
sudo apt install make gcc ripgrep unzip git xclip neovim
```
</details>

#### Linux Install
<details><summary>Ubuntu Install Steps</summary>

```
sudo add-apt-repository ppa:neovim-ppa/unstable -y
sudo apt update
sudo apt install make gcc ripgrep unzip git xclip neovim
```
<details><summary>Arch Install Steps</summary>

```
sudo pacman -S --noconfirm --needed gcc make git ripgrep fd unzip neovim
```
</details>

