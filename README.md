VIM integration via P4Python
===============================================

Disclaimer
----------
Fork from [brettbates/vim-p4][]. Original author is Randy DeFauw, and initial project was published on [Perforce Public Depot](http://public.perforce.com:8080/@md=d&amp;cd=//guest/randy_defauw/&amp;c=hZW@//guest/randy_defauw/vim_p4/?ac=83).

See also the article by the original author on [Perforce blog](https://www.perforce.com/blog/101123/perforce-integration-vim-courtesy-p4python).

Requirements
------------
P4Vim requires the following:
* Vim compiled with Python support (+python or +python/dyn).
* The P4Python API (http://www.perforce.com/product/components/apis).

Optionnally, to use the revision graph (:P4RevGraph), also requires Perl with Graph::Easy module.

Installation
------------
Vundle is the recommended way to install vim-p4. Add this line to your .vimrc:

    Bundle 'sebhg/vim-p4'

Then run `:PluginInstall` inside Vim.

Usage
-----
Uses the connection environment from the current working directory.

Oriented towards commands that can be run on a single file.

Get help by typing :help vimp4python.


License
-------
Copyright (c) Perforce Software, Inc., 1997-2010. All rights reserved

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1.  Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.

2.  Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
'AS IS' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL PERFORCE
SOFTWARE, INC. BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR
TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF
THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH
DAMAGE.

User contributed content on the Perforce Public Depot is not supported by Perforce,
although it may be supported by its author. This applies to all contributions 
even those submitted by Perforce employees.

Related projects
----------------
* [nfvs/vim-perforce](https://github.com/nfvs/vim-perforce)
* [verbitan/P4Vim](https://github.com/verbitan/P4Vim)
* [Hari Krishna Dara's vim-perforce][]
* [Tom Slee's perforce.vim][]

[Tom Slee's perforce.vim]: https://github.com/vim-scripts/perforce.vim
[Hari Krishna Dara's vim-perforce]: https://github.com/idbrii/vim-perforce
[brettbates/vim-p4]: https://github.com/brettbates/vim-p4#about
