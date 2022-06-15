# Shared resources
This is a collection of things I found useful, generally with my own usage notes. Your mileage may vary.

## Isabelle
### Macro: isabelle-to-ascii
```./isabelle/isa-to-ascii/```

Simple jEdit macro to grab a line selection in a utf8-isabelle file, and place its ASCII contents into the clipboard.

## (La)TeX
### lisa.sty
```./tex/lisa/```
The package is just a wrapper around some configuration for the `listings` package. Currently there's a monochrome option for prin
ting etc, but the default is to colorfully highlight syntax in listings. It provides configuration for the usual `lstlisting` envi
ronment, and a command `\lisa` for inline listings. See also the example `mwe_lisa.tex`.

This directory also contains a `setup.tex` file with some configuration I use often, for use with `\input` in the preamble. I plan
 to keep updating this.

### rebuttal.sty
```./tex/rebuttal/```

*Forked from Simon Butler's [repo](https://github.com/sjbutler/rebuttal).*

The rebuttal LaTeX class provides environments and macros to format a point by point response to a journal article review. A section can be defined for each reviewer and the reviewer's points are automatically numbered. Labels can be added to the reviewers' points so that they can be cross referenced from responses.

The class can be used to format the rebuttal serially, i.e. reviewer's point followed by authors' response, or as two columns so that the authors' response appears alongside the reviewer's comment.
