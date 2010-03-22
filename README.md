# LESS TextMate Bundle

This bundle adds CSS syntax highlighting to `.less` files with the ability to compile to `.css` files (⌘B). To learn more about [LESS][], see the [docs](http://lesscss.org/docs.html).

This bundle was forked from `appden/less.tmbundle` but has since been rewritten from scratch (the language syntax).

## Compiling to CSS (⌘B)

Runs `lessc` on the current file, saving to the same file name with a .css extension (e.g. style.less => style.css). When there is `lessc: somefile.less` somewhere in the current file, that file is compiled instead.

Compiling requires some version of `lessc` to be in your `PATH`.

## Authors

* Rasmus Andersson <http://hunch.se/> rsms@github
* Scott Kyle <http://appden.com/> appden@github

## License

* This bundle is open source under an MIT-style license

[LESS]: http://lesscss.org
