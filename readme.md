# spacemacs-theme.vim

A theme modelled after [nashamri/spacemacs-theme](https://github.com/nashamri/spacemacs-theme/), for Vim and iTerm. Intended for use only in true-colour terminals. Work in progress.

![](screenshots/jsx-demo.png)
![](screenshots/error.png)

## Usage

### Vim
Use your favourite plugin manager to track this repo (`colepeters/spacemacs-theme.vim`). Then specify the following in your `.vimrc` / `init.vim` (only tested in Neovim):

```vimL
if (has("termguicolors"))
  set termguicolors
endif
set background=dark
colorscheme spacemacs-theme
```

### iTerm2
Download the repo, and open the `.itermcolors` file from Finder. Ta-da!
