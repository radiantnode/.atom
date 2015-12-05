# My ~/.atom config directory

Sharing my setup for the [Atom](http://atom.io) text editor

Uses a package management strategy by [substantial/atomfiles](https://github.com/substantial/atomfiles)

----

## Included Packages

* [alignment](https://github.com/blakeembrey/atom-alignment)
* [atom-bootstrap3](https://github.com/f/atom-bootstrap3)
* [atom-bootstrap4](https://github.com/mdegoo/atom-bootstrap4)
* [file-icons](https://github.com/DanBrooker/file-icons)
* [git-control](https://github.com/jacogr/atom-git-control)
* [language-haml](https://github.com/ezekg/language-haml)
* [language-nginx](https://github.com/hnagato/atom-language-nginx)
* [minimap](https://github.com/atom-minimap/minimap)
* [minimap-pigments](https://github.com/abe33/minimap-pigments)
* [rails-snippets](https://github.com/joseramonc/rails-snippets)

## Setup

```bash
cd ~
# If you have an atom config already:
mv .atom .atom-bak
git clone git@github.com:radiantnode/.atom.git .atom
cd .atom && bin/update-packages
```