# 🦉 Night-Owl theme for Neovim

<p align="center">
  <img width="860" alt="Night Owl syntax" src="https://user-images.githubusercontent.com/1166872/64192497-645d2200-cead-11e9-9c79-0b5fdc0955c9.png">
</p>
<p align="center">
  <small>Font in the above screenshot is <a href="https://github.com/be5invis/Iosevka">Iosevka</a></small>
</p>
<p align="center">
  <img width="860" alt="Night Owl Vim colorscheme screenshot" src="https://user-images.githubusercontent.com/1166872/58341756-8f34e480-7e81-11e9-90d1-19775d6020bd.png">
</p>
<p align="center">
  <small>Font in the above screenshot is <a href="https://github.com/belluzj/fantasque-sans">Fantasque Sans Mono</a></small>
</p>

A true color Vim colorscheme based on
[sdras/night-owl-vscode-theme](https://github.com/sdras/night-owl-vscode-theme)

## ⌨️ Usage

```vim
""""" install

" install with vim-plug
Plug 'oxfist/night-owl.vim'
" or with NeoBundle
" NeoBundle 'oxfist/night-owl.vim'
" or with Vundle
" Plugin 'oxfist/night-owl.vim'

""""" enable 24bit true color

" If you have vim >=8.0 or Neovim >= 0.1.5
if (has("termguicolors"))
 set termguicolors
endif

" For Neovim 0.1.3 and 0.1.4
let $NVIM_TUI_ENABLE_TRUE_COLOR=1

""""" enable the theme

syntax enable
colorscheme night-owl

" To enable the lightline theme
let g:lightline = { 'colorscheme': 'nightowl' }
```

## 🎨 Customize

This theme is built with
[jacoborus/estilo](https://github.com/jacoborus/estilo). If you want to
customize this theme, you will need [Node.js](https://nodejs.org).

Edit `estilo/palettes/night-owl.vim.yml` and `estilo/syntax/base.yml` to
customize this theme.

Read
[How to define Color Palettes for Estilo](https://github.com/jacoborus/estilo/blob/master/docs/color-palettes.md)
and
[How to define Colorschemes for Estilo](https://github.com/jacoborus/estilo/blob/master/docs/colorschemes.md)
to understand how to use them.

```bash
# clone the repo and cd to the dir
# install deps
# you can use npm too
$ yarn

# make changes and run
$ yarn render
```

## 🔗 Links

- [How to define Color Palettes for Estilo](https://github.com/jacoborus/estilo/blob/master/docs/color-palettes.md)
- [How to define Colorschemes for Estilo](https://github.com/jacoborus/estilo/blob/master/docs/colorschemes.md)
- [24bit(true color) in terminal](https://github.com/termstandard/colors)
- [jacoborus/estilo](https://github.com/jacoborus/estilo)
