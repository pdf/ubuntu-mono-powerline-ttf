ubuntu-mono-powerline-ttf
=========================

Ubuntu Mono fonts patched for [vim-powerline](https://github.com/Lokaltog/vim-powerline/) and the new [powerline](https://github.com/Lokaltog/powerline/)

Installation
-------------------------
```bash
git clone https://github.com/pdf/ubuntu-mono-powerline-ttf.git ~/.fonts/ubuntu-mono-powerline-ttf
fc-cache -vf
```

### powerline ###

Set your terminal font to <tt>Ubuntu Mono for Powerline</tt> and for gvim, add:
```
set guifont=Ubuntu\ Mono\ for\ Powerline\ 12
```
to your <tt>.vimrc</tt>, where <tt>12</tt> is the font size.


### vim-powerline ###

Set your terminal font to <tt>Ubuntu Mono for VimPowerline</tt> and for gvim, add:
```
set guifont=Ubuntu\ Mono\ for\ VimPowerline\ 12
```
to your <tt>.vimrc</tt>, where <tt>12</tt> is the font size.

As usual, make sure you have <tt>let g:Powerline_symbols = 'fancy'</tt> in your
<tt>.vimrc</tt> to enable the fancy glyphs.
