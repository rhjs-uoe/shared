# Overview
The `isa-to-ascii` macro is meant to be used on Isabelle/HOL theory files loaded with the `utf8-isabelle` encoding in jEdit.
It will grab all the lines in your current selection (full lines, i.e. starting halfway through a line grabs that line too) and put them in your copy/paste register as plain ASCII.
Useful for pasting e.g. into LaTeX listings.
It will only work if you **save your file first** (currently I can't manage to do that from `.bsh` without breaking other things).

This macro will **overwrite** your current clipboard/copy register's contents.

# Setup
1. Copy the file `isa-to-ascii.bsh` into `$ISABELLE_HOME_USER/jedit/macros`.
1. In Isabelle/jEdit, you should now see `isa-to-ascii` listed under the `Macros` menu (all the way at the bottom; you may need to `Rescan Macros` in the same menu).
1. In the Options Dialog (`Utilities > Global Options`), you should find `Shortcuts` under the `jEdit` tab on the left.
1. Search for `isa-to-ascii` and assign a shortcut of your choice.
