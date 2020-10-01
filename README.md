# Molokai Color Scheme for Vim

Molokai is a Vim port of the monokai theme for TextMate originally created by Wimer Hazenberg.

By default, it has a dark gray background based on the version created by Hamish Stuart Macpherson for the E editor.

![Gray Background](https://user-images.githubusercontent.com/13169164/94844241-91973f00-03e3-11eb-8610-425c0da15395.png)

![Molokai Original](https://user-images.githubusercontent.com/13169164/94845684-a674d200-03e5-11eb-9d1d-3a35ff949b3b.png)

256-Color terminals are also supported, though there are some differences with the Gui version. Only the dark gray background style is supported on terminal vim at this time.

## Installation

Copy the file on your .vim/colors folder.

If you prefer the scheme to match the original monokai background color, put this in your .vimrc file:
```sh
let g:molokai_original = 1
```

There is also an alternative scheme under development for color terminals which attempts to bring the 256 color version as close as possible to the the default (dark) GUI version. To access, add this to your .vimrc:
```sh
let g:rehash256 = 1
```

