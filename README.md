# Twilight Anti-Bright

A light-on-dark Emacs and TextMate theme inspired by the dark-on-light
Twilight Bright TextMate theme by [Florian Pichler][pichfl].

[pichfl]: http://einserver.de/goodies

## Supported Editors

* Emacs
* TextMate (beta)
* Any editor with support for TextMate themes

## Preview

Emacs (Mac OS X Cocoa):

<div style="text-align: center">
  <img src="https://github.com/jimeh/twilight-anti-bright-theme/raw/master/preview/emacs-gui.png" alt="preview" />
</div>

TextMate:

<div style="text-align: center">
  <img src="https://github.com/jimeh/twilight-anti-bright-theme/raw/master/preview/textmate.png" alt="preview" />
</div>

## Installation & Usage

### Emacs 24

If you're using [MELPA][] there's a `twilight-anti-bright-theme` package
available. Otherwise follow these instructions:

[melpa]: http://melpa.milkbox.net/

1. Add the `twilight-anti-bright-theme` directory to your Emacs `load-path`
   and `custom-theme-load-path`.
2. Add one of the following to your Emacs init file:
    - `(require 'twilight-anti-bright-theme)`
    - `(load-theme twilight-anti-bright t)`
3. Reload the init file, or restart Emacs.

### TextMate

1. Download [Twilight Anti-Bright.tmtheme][tmtheme] and open it with TextMate.
2. Done.

[tmtheme]: https://github.com/jimeh/twilight-anti-bright-theme/raw/master/Twilight%20Anti-Bright.tmTheme

## Todos

* Potentially improve TextMate version. It was thrown together really quickly
  without getting much use as I personally don't use TextMate anymore.

## Contribute

Feel free to send pull requests for adding support for additional editors
or to fix/tweak any issues :)

## License

(The MIT license)

Copyright (c) 2012 Jim Myhrberg.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
