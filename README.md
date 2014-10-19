# Molokai Color Scheme for Vim

Molokai is a Vim port of the monokai theme for TextMate originally created by Wimer Hazenberg.

By default, it has a dark gray background based on the version created by Hamish Stuart Macpherson for the E editor.

![Gray Background](http://www.winterdom.com/weblog/content/binary/WindowsLiveWriter/MolokaiforVim_8602/molokai_normal_small_3.png)

![Molokai Original](http://www.winterdom.com/weblog/content/binary/WindowsLiveWriter/MolokaiforVim_8602/molokai_original_small_3.png)

256-Color terminals are also supported, though there are some differences with the Gui version. Only the dark gray background style is supported on terminal vim at this time.

## Installation

Copy the colors/molokai.vim file to your .vim/colors folder

```bash
# Assumes .vim is in your home directory
$ mkdir -p $HOME/.vim/colors
$ curl https://raw.githubusercontent.com/tomasr/molokai/master/colors/molokai.vim > $HOME/.vim/colors/molokai.vim
```

Enable the molokai color scheme in .vimrc

```bash
$ printf '" Enable molokai colorscheme\n" https://github.com/tomasr/molokai\ncolorscheme molokai' >> $HOME/.vimrc
```

## Settings

If you prefer the scheme to match the original monokai background color, put this in your .vimrc file: 
```
let g:molokai_original = 1
```

There is also an alternative scheme under development for color terminals which attempts to bring the 256 color version as close as possible to the the default (dark) GUI version. To access, add this to your .vimrc:
```
let g:rehash256 = 1
```

