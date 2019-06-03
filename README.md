# fzf Plugin For Vim
Based on [`junegunn/fzf`](https://github.com/junegunn/fzf/blob/master/README-VIM.md) with same functionality.

## Changes 
- `g_fzf_open_action`: 
  - Customize action when opening buffer (default: 'e')
```vim
" Open file in new tab
let g_fzf_open_action = 'tab split'
```
