---
layout: article
title: Installation
tags: php-mode
sidebar:
  nav: php-mode
---

We provide several PHP Mode installation methods.

## Install via package.el

Modern Emacs extensions (often called **Lisp package**) can be installed from **ELPA** (*GNU Emacs Lisp Package Archive*).

However, PHP Mode is not registered in default repository ([GNU ELPA]) due to [historical reason][Will GNU Emacs Ever Include php mode?].

### Add MELPA to package-archives

If you have not already registered MELPA in `package-archives`, read [Getting Started - MELPA] and add MELPA.

### M-x list-packages

Press `M-x list-package` and search **php-mode** package.  If you find **php-mode**, typing `I` followed by `x` will install the package.


[Getting Started - MELPA]: https://melpa.org/#/getting-started
[GNU ELPA]: https://elpa.gnu.org/
[MELPA]: https://melpa.org/
[Will GNU Emacs Ever Include php mode?]: https://github.com/emacs-php/php-mode/wiki/Will-GNU-Emacs-Ever-Include-php-mode%3F
