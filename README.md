# Guides

- [Emacs](#emacs)
- [Make](#make)

## Emacs

Emacs is the extensible, customizable, self-documenting real-time
display editor. You can run Emacs in the terminal with no window using
`emacs -nw` (short for --no-window-system) or use the GUI version.

Perhaps the most standard Emacs command line option is outputing the version info with:

```
$ emacs --version
GNU Emacs 29.3
Copyright (C) 2024 Free Software Foundation, Inc.
GNU Emacs comes with ABSOLUTELY NO WARRANTY.
You may redistribute copies of GNU Emacs
under the terms of the GNU General Public License.
For more information about these matters, see the file named COPYING.
```

This guide uses shorthand notation for key combinations. For example to
exit Emacs type `Control-x` followed by `Control-c` which is written as
`C-x C-c`. We also use `RET` in place of typing enter or return.

A great way to open Emacs and jump straight into a buffer for Lisp evaluation is to run:

`$ emacs --no-splash`

Just enter some Lisp commands for evaluation and execute with `C-j`.

After starting emacs the integrated tutorial can be run with `C-h t`. The prefix key `C-h`
stands for "help". To stop the tutorial type `C-x k RET`.

When using Emacs on a graphical display you can use `C-z` to minimize the window. If you have
a file named `emacs.txt` in your home directory you can use `C-x C-f emacs.txt RET` to begin
editing this file. The command `C-x C-f` (find-file) accepts a filename as an argument. When
you are done editing your file you can save with `C-x C-s`.

There are some nice command line display options including:

- `--background-color, -bg COLOR`  window background color
- `--title, -T TITLE`  title for initial Emacs frame

## Make


