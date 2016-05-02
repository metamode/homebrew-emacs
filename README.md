This is a fork of the core Emacs homebrew formula @ https://github.com/Homebrew/homebrew-core/blob/master/Formula/emacs.rb , with some added patches to builtin packages.

Currently it patches the builtin cc-mode package to handle the "auto" keyword in C++ as a type only, rather than a keyword, which fixes some issues surrounding font highlighting in >=C++11 code. Pre-C++11 uses of auto are not disregarded with this patch in place.
