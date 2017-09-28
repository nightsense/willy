# willy

A vim theme inspired by the [Amazing Chocolatier keycap set](http://zambumon.github.io/) by Zambumon.

## screenshots

<table>
<tr></tr><tr><td align="center"><strong>willy-<br>light</strong></td>
<td align="center"><img src="img/screenshot-willy-light.png" alt="screenshot of the willy-light vim theme" width="288"> <img src="img/screenshot-willy-dark.png" alt="screenshot of the willy-dark vim theme" width="288"></td>
<td align="center"><strong>willy-<br>dark</strong></td></tr>
</table>

## installation

### step 1: download the colour scheme

#### option A: manually

Download the [colourscheme files](https://github.com/nightsense/willy/tree/master/colors) and place in directory `~/.vim/colors/` (Linux/Mac) or `%userprofile%\vimfiles\colors\` (Windows).

#### option B: using a plugin manager

For easy management of Vim colour schemes (and other plugins), try a plugin manager. With [vim-plug](https://github.com/junegunn/vim-plug), for instance, just add `Plug 'nightsense/willy'` to the list of plugins in your `vimrc`, then run `PlugUpdate`.

### step 2: activate the colour scheme

To activate the willy theme, add one of the following lines to your `vimrc`:

- `colorscheme willy-light`
- `colorscheme willy-dark`

To assign themes to specific intervals of the day, try the [night-and-day](https://github.com/nightsense/night-and-day) plugin.

## terminal vim

To make this theme work in terminal vim, install [nightshell](https://github.com/nightsense/nightshell) to `~/.nightshell`:

```
git clone https://github.com/nightsense/nightshell ~/.nightshell
```

## notes

This theme was created using Chris Kempson's [base16](https://github.com/chriskempson/base16-vim) as a template.
