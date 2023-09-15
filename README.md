# lion.vim fork

https://github.com/tommcdo/vim-lion

Added a new global option to change the keymap of `/` (prompt for pattern after motion).

```viml
let g:lion_prompt_map = "<Tab>"
```

It's a bit rough, for example, didn't work when trying to map to `<BS>` (backspace), `ä` or `€`.
