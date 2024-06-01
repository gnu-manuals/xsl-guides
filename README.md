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
`C-x C-c`.

A great way to open Emacs and jump straight into a buffer for Lisp evaluation is to run:

`$ emacs --no-splash`

Just enter some Lisp commands for evaluation and execute with `C-j`.

After starting emacs the integrated tutorial can be run with `C-h t`

## Make


