Luadist-git
===========

[![Build Status](https://secure.travis-ci.org/LuaDist/luadist-git.png?branch=master)](http://travis-ci.org/LuaDist/luadist-git)

Luadist-git is [Lua](http://lua.org) module deployment utility for the [LuaDist](https://github.com/LuaDist) project. In fact it's another version of older [luadist utility](https://github.com/LuaDist/luadist), rewritten from scratch.

Main Goals
----------

 * access git repositories directly (through git) and get rid of unnecessary
   dependencies (i.e. luasocket, luasec, md5, openssl, unzip) - **DONE**

 * use _.gitmodules_ as a repository manifest file instead of _dist.manifest_,
   thus removing the need to update the manifest after every change in modules  - **DONE**

 * add functionality for uploading binary versions of modules to repositories

 * once [libgit2](https://github.com/libgit2/libgit2) matures, use it instead of the git cli command


Useful links
----------
* [Bug tracker](https://github.com/LuaDist/luadist-git/issues)
* [LuaDist documentation](https://github.com/LuaDist/Repository/wiki)

<br>
Under the MIT License.

