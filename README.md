# My ~/.atom config

Sharing my setup for the [Atom](http://atom.io) text editor

Uses a package management strategy by [substantial/atomfiles](https://github.com/substantial/atomfiles)

----

## Included Packages

* [alignment](https://github.com/blakeembrey/atom-alignment)
* [atom-bootstrap3](https://github.com/f/atom-bootstrap3)
* [atom-bootstrap4](https://github.com/mdegoo/atom-bootstrap4)
* [close-after-last-tab](https://github.com/JRHeaton/atom-close-after-last-tab)
* [emmet](https://github.com/emmetio/emmet-atom)
* [file-icons](https://github.com/DanBrooker/file-icons)
* [gist](https://github.com/aki77/atom-gist)
* [git-control](https://github.com/jacogr/atom-git-control)
* [language-haml](https://github.com/ezekg/language-haml)
* [language-nginx](https://github.com/hnagato/atom-language-nginx)
* [minimap](https://github.com/atom-minimap/minimap)
* [open-in-browser](https://github.com/magbicaleman/open-in-browser)
* [open-recent](https://github.com/Zren/atom-open-recent)
* [pigments](https://github.com/abe33/atom-pigments)
* [rails-snippets](https://github.com/joseramonc/rails-snippets)
* [terminal-plus](https://github.com/jeremyramin/terminal-plus)

## Setup

```bash
cd ~
# If you have an atom config already:
mv .atom .atom-bak
git clone git@github.com:radiantnode/.atom.git .atom
cd .atom && bin/update-packages
```