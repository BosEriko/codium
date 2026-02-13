# VSCodium (Editor)
Download [Nix](https://github.com/BosEriko/nix) as your package manager then install [VSCodium](https://search.nixos.org/packages?channel=25.11&query=vscodium&show=vscodium).

## Install kmonad
```sh
home.packages = with pkgs; [
  vscodium
  neovim
];
```

## Clone the Repository
```sh
mkdir -p ~/.config/VSCodium
git clone https://github.com/BosEriko/codium.git ~/.config/VSCodium/User
```
