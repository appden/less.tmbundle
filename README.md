LESS TextMate Bundle
====================

This bundle adds CSS syntax highlighting to .less files and parses them to .css files on save (⌘S).  To learn more about [LESS][], see the [docs](http://lesscss.org/docs.html).

Requirements
------------

`sudo gem install less`

Save to CSS (⌘S)
----------------

Runs `lessc` on the current file, saving to the same file name with a .css extension (e.g. style.less => style.css).
When there is `lessc: somefile.less` somewhere in the current file, that file is compiled instead.

Language Grammar
----------------

Not all LESS-specific grammars are added yet, if you'd like to do so, please fork and send a pull request.

Licenses
--------

* This bundle is open source under an MIT-style license
* [LESS][] is open source under the Apache license


[LESS]: http://lesscss.org
