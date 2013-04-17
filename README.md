# Hungry 

Hungry provides a two column view of code and documentation. It will
turn any definition that refers to a function in another file into a link to
that file and it's accompanying documentation.

Hungry Supports both inline documentation, and mirrored directory structured
documentation. 

Should be a commandline service that renders a directory and all of it's
subdirectories. You can include a .hun-ignore file in your project root which
will prevent Hungry from traversing the listed files and directories.

The documentation website will be in the `hun-doc` directory. It also includes
a configurable hook so that any time you commit (whether in `hg`, `git`, etc.)
it will run. May be better to run on push, since commits should stay light
weight.


