# My Vim config

![.vimrc](https://i.imgur.com/VboV6Fb.png)

## Features

- Coding with Go.
- Themes: PaperColor (default), Dracula.
- Support for tmux.
- Airline theme: simple.
- Press `gd` for go to definition.
- Press `gr` for references.
- Ctrl+Shif+e for open NERDtree.
- Autocomplete.

## Install

1. Put `.vimrc` file in `~/` and then run:

```bash
$ vim .vimrc
```

2. Run inside Vim:

```
:PlugInstall
:CocInstall coc-go coc-json coc-tsserver @yaegassy/coc-intelephense
```

3. Close and open again.
