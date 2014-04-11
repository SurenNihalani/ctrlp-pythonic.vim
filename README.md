ctrlp-pythonic
==============

Python code navigation extension for the [Ctrl-P](https://github.com/kien/ctrlp.vim) fuzzy-finder plugin for [Vim](http://www.vim.org).


Requirements
------------

- [ctrlp.vim](https://github.com/kien/ctrlp.vim)


Installation
------------

### [pathogen.vim](https://github.com/tpope/vim-pathogen)

    $ cd ~/.vim/bundle
    $ git clone git://github.com/tacahiroy/ctrlp-pythonic.git


### [Vundle](https://github.com/gmarik/vundle.git)

    :BundleInstall tacahiroy/ctrlp-funky

Add the line below into your _.vimrc_.

    Bundle 'tacahiroy/ctrlp-pythonic'

### Manually

Copy the _autoload_ and _plugin_ sub-directories to your _.vim_ directory (on
Windows: _vimfiles_).

Configuration
-------------

You need to make the plugin available as a ctrlp.vim extension. Add *pythonic* to the variable `g:ctrlp_extensions` in your _.vimrc_:

    let g:ctrlp_extensions = ['pythonic']

Commands and Key-Mappings
-------------------------

The `:CtrlPPythonic` command will be available to directly invoke Ctrl-P in `pythonic` mode.

This is not bound to any key-mapping by default, so you may want to add the following to your _.vimrc_:

    nnoremap <Leader>/ :CtrlPPythonic<Cr>

License
-------

Copyright 2014 Jeet Sukumaran

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
