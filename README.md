:TUT
====

Toggles betwixt source and unit test file

Introduction
------------

Use this plug-in when you are doing Test-Driven Development [TDD] in any
language to quickly switch between unit-test and production code. To make this
really fast, bind the TUT command to a function key in your `$VIMRC`:

```
    "   [F3]    toggles between (header, ) source and test files.
    nnoremap    <F3> :<C-U>TUT<CR>
```

This plug-in assumes source and unit test files are in the same directory.

Installation
------------

I recommend installing [pathogen.vim](https://github.com/tpope/vim-pathogen),
and then simply copy and paste:

    cd ~/.vim/bundle
    git clone git://github.com/johnsyweb/vim-tut.git

Once help tags have been generated, you can view the manual with
`:help toggle_unit_tests`.

Mappings
--------

`<Leader>tut`

Toggles betwixt source and unit test file

Commands
--------

`:TUT`

Toggles betwixt source and unit test file

Settings
--------

By default, unit-test filenames are deemed to begin with 't_'.

Tell toggle_unit_tests.vim your own prefix by setting the following global
variable, perhaps in `$VIMRC`:

    let g:unit_test_prefix='test_'

Thanks
------

If you find this plug-in useful, please follow this repository on
[GitHub](https://github.com/johnsyweb/vim-tut) and vote for it on
[vim.org](http://www.vim.org/scripts/script.php?script_id=2500). If you have
something to say, you can contact [johnsyweb](http://johnsy.com/about/) on
[Twitter](http://twitter.com/johnsyweb/) and
[GitHub](https://github.com/johnsyweb/).


