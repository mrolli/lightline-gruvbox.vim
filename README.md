lightline-gruvbox
=================

Overview
-----------------
lightline-gruvbox is a [lightline.vim](https://github.com/itchyny/lightline.vim) theme for the fantastic [gruvbox](https://github.com/morhetz/gruvbox) colorscheme, deeply inspired by [lightline-hybrid](https://github.com/cocopon/lightline-hybrid.vim).

The original repo [light-line-gruvbox.vim](https://github.com/shinchu/lightline-gruvbox.vim) by shinchu has been forked by me to improve certain aspects:

The color yellow is now also available and used for warning. Warnings and erros were previously missing. You can now use them in your lightline configuration like this:

```
let g:lightline.component_type': {
  \   'linter_checking': 'right',
  \   'linter_infos': 'right',
  \   'linter_warnings': 'warning',
  \   'linter_errors': 'error',
  \   'linter_ok': 'ok',
}
```

Installation
----------------
Use your favourite plugin manager.
```vim
Plug 'shinchu/lightline-gruvbox.vim'
```

Add the following lines to your `.vimrc`.
```vim
let g:lightline = {}
let g:lightline.colorscheme = 'gruvbox'
```

Screenshots
----------------
### Dark
![dark](https://raw.githubusercontent.com/shinchu/images/master/lightline-gruvbox/dark.png)

### Light
![light](https://raw.githubusercontent.com/shinchu/images/master/lightline-gruvbox/light.png)
