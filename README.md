# README

**help doc not working right now**

_vim-lx_ provides integration to linux command line tools I find useful

The thought being that some of the tools are useful within an editor,
operating on a range of lines, rather than simply on an entire file.


## VlxColumn

The simplest of all interfaces to _column_. As markdown tables and dat files
typically use the pipe character to separate values, the pipe is identified
to column as both separator and output separator.

Goals, in no particular order:

+ [x] simple use as alignment tool on .dat files and markdown/rmd tables
+ [ ] provide ability to override pipe as separator character
+ [ ] provide ability to override pipe as output separator character
+ [ ] provide option to right-align some columns using column's alignment option
+ [ ] provide access to other options as they come up
