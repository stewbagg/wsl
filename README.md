<a id="readme-top"></a>

[![Stargazers][stars-shield]][stars-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
   <a href="https://github.com/stewbagg/dotfiles">
      <img src="assets/wsl.png" alt="WSL logo" width="80" height="80">
   </a>

   <h3 align="center">WSL</h3>

   <p align="center">
      Configuration files for my WSL environment.
      <br />
   </p>
</div>

<details>
   <summary>Table of Contents</summary>
   <ol>
      <li>
         <a href="#about">About</a>
         <ul>
            <li><a href="#tech-stack">Tech Stack</a></li>
         </ul>
      </li>
      <li><a href="#installation">Installation</a></li>
   </ol>
</details>

## About

This configuration aims to be as minimalist/brutalist as possible.

Goals:

- System consistency
- Environment reusability
- Eliminate configuration overhead

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Tech Stack

- [![Arch][Arch.icon]][Arch-url]
- [![Git][Git.icon]][Git-url]
- [![GitHub][GitHub.icon]][GitHub-url]
- [![Neovim][Neovim.icon]][Neovim-url]
- [![Windows][Windows.icon]][Windows-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Installation

1. Clone the repo

```bash
git clone https://github.com/stewbagg/dotfiles ~/wsl
```

2. CD into the new folder

```bash
cd ~/wsl
```

3. Create symbolic links using Stow

```bash
stow . # all files/folders or stow .bashrc .config/nvim etc.
```

4. Remove symbolic links using Stow

```bash
stow -D . # all files/folders or stow .bashrc .config/nvim etc.
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[stars-shield]: https://img.shields.io/github/stars/stewbagg/dotfiles.svg?style=for-the-badge
[stars-url]: https://github.com/stewbagg/dotfiles/stargazers
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/spencer-dennison
[Arch.icon]: https://img.shields.io/badge/Arch%20Linux-1793D1?logo=arch-linux&logoColor=fff
[Arch-url]: https://archlinux.org/
[Git.icon]: https://img.shields.io/badge/Git-F05032?logo=git&logoColor=fff
[Git-url]: https://git-scm.com/
[GitHub.icon]: https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white
[GitHub-url]: https://github.com/
[Neovim.icon]: https://img.shields.io/badge/Neovim-57A143?logo=neovim&logoColor=fff
[Neovim-url]: https://neovim.io/
[Windows.icon]: https://custom-icon-badges.demolab.com/badge/Windows-0078D6?logo=windows11&logoColor=white
[Windows-url]: https://www.microsoft.com/en-us/
