<a id="readme-top"></a>

# Installation

1. Clone the repo

```bash
git clone https://github.com/stewbagg/dotfiles ~/wsl
```

2. CD into the folder

```bash
cd ~/wsl
```

3. Create symbolic links using GNU Stow

```bash
stow . # all files/folders or stow .bashrc .config/nvim etc.
```

4. Remove symbolic links using GNU Stow

```bash
stow -D . # all files/folders or stow .bashrc .config/nvim etc.
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>
