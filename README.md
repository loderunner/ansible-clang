Clang [![Ansible Role](https://img.shields.io/ansible/role/d/21596.svg)](https://galaxy.ansible.com/loderunner/clang/) [![Build Status](https://travis-ci.org/loderunner/ansible-clang.svg?branch=master)](https://travis-ci.org/loderunner/ansible-clang)
=====

Ansible role that installs [Clang](https://clang.llvm.org/) to Ubuntu or Debian.

Role Variables
--------------

`clang_version`: Which version of Clang to install. Possible values: `5.0`, `6.0`, `7`. Default is `7`.

`set_clang_cc`: Whether or not to set Clang as the default C compiler, using the `CC` environment variable for all users. The default is `false`.

License
-------

The MIT License (MIT)

Copyright (c) 2017 Charles Francoise

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Author Information
------------------

You can find me on [Twitter](https://twitter.com/loderunnr), [GitLab](https://gitlab.com/loderunner) and on [GitHub](https://github.com/loderunner/). I work on [Pantomath](https://pantomath.io) and sometimes write on [ThePracticalDev](https://dev.to/loderunner).
