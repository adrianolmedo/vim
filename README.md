![.vimrc](https://i.imgur.com/VboV6Fb.png)

# My personal Vim config

- Adapted for coding with Go.
- Theme: ColorPaper.
- Airline theme: simple.
- Press `gd` for go to definition.
- Press `gr` for references.
- Ctrl+Shif+e for open NERDtree.
- Autocomplete.

## Install

1. Get the .vimrc file in ~/ and then run `$ vim .vimrc`.

2. Run inside vim:

```
:PlugInstall
:CocInstall coc-go coc-json coc-tsserver
```
