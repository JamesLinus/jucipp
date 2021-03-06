# juCi++ [![Build Status](https://travis-ci.org/cppit/jucipp.svg?branch=master)](https://travis-ci.org/cppit/jucipp) [![Build status](https://ci.appveyor.com/api/projects/status/tj8ants9q8ouuoob/branch/master?svg=true)](https://ci.appveyor.com/project/zalox/jucipp-6hwdu/branch/master)

###### a lightweight, platform independent C++-IDE with support for C++11, C++14, and experimental C++17 features depending on libclang version.
<!--<img src="https://github.com/cppit/jucipp/blob/master/docs/images/screenshot3.png"/>-->
## About
Current IDEs struggle with C++ support due to the complexity of
the programming language. juCI++, however, is designed especially 
towards libclang with speed, stability, and ease of use in mind. 

## Features
* Platform independent
* Fast, responsive and stable (written extensively using C++11/14 features)
* Syntax highlighting for more than 100 different file types
* C++ warnings and errors on the fly
* C++ Fix-its
* Debug integration, both local and remote, through lldb
* Supports the following build systems:
  * CMake
  * Meson
* Git support through libgit2
* Fast C++ autocompletion
* Keyword and buffer autocompletion for other file types
* Tooltips showing type information and doxygen documentation (C++)
* Rename refactoring across files (C++)
* Highlighting of similar types (C++)
* Automated documentation search (C++)
* Go to declaration, implementation, methods and usages (C++)
* Find symbol through Ctags
* Spell checking depending on file context
* Run shell commands within juCi++
* Regex search and replace
* Smart paste, keys and indentation
* Auto-indentation of C++ file buffers through [clang-format](http://clang.llvm.org/docs/ClangFormat.html)
* Source minimap
* Split view
* Full UTF-8 support
* Wayland supported with GTK+ 3.20 or newer

See [enhancements](https://github.com/cppit/jucipp/labels/enhancement) for planned features.

## Screenshots
<table border="0">
<tr>
<td><img src="https://github.com/cppit/jucipp/blob/master/docs/images/screenshot1c.png" width="380"/></td>
<td><img src="https://github.com/cppit/jucipp/blob/master/docs/images/screenshot2c.png" width="380"/></td>
</tr><tr>
<td><img src="https://github.com/cppit/jucipp/blob/master/docs/images/screenshot3c.png" width="380"/></td>
<td><img src="https://github.com/cppit/jucipp/blob/master/docs/images/screenshot4b.png" width="380"/></td>
</tr>
</table>

## Dependencies
* boost-filesystem
* boost-serialization
* gtkmm-3.0
* gtksourceviewmm-3.0
* aspell
* libclang
* lldb
* libgit2
* [libclangmm](http://github.com/cppit/libclangmm/) (downloaded directly with git --recursive, no need to install)
* [tiny-process-library](http://github.com/eidheim/tiny-process-library/) (downloaded directly with git --recursive, no need to install)

## Installation
See [installation guide](docs/install.md).

## Documentation
See [how to build the API doc](docs/api.md).
