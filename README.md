# The `lccaps` package

This tiny package serves the mere purpose of
providing a uniform method to use
lowercased small capitals (and spaced lowercased small capitals).
It relies on the `iftex`, `textcase` and `microtype` package
and comes with four new user macros:
  `\textlcc`,
      the main feature: lowercased small capitals,
  `\spacedcaps`,
      a prefix to small capitals text commands
      to slightly increase their spacing,
  `\textslcc` and
  `\textssc`,
which are shortcuts for `\spacedcaps\textlcc`
and `\spacedcaps\textsc` (accordingly).

This is version 1.0 of the package.

Copyright (C) 2018 by Ruben Giannotti

---

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either
version 1.3c of this license or (at your option) any
later version. The latest version of this license is in
  http://www.latex-project.org/lppl.txt
and version 1.3 or later is part of all distributions
of LaTeX version 2005/12/01 or later.

This work has the LPPL maintenance status `maintained'.

The Current Maintainer of this work is Ruben Giannotti.

This work consists of the files
   lccaps.dtx,
   lccaps.ins
and the derived file lccaps.sty.

To install the package

 1. run `latex lccaps.ins`
 2. move 'lccaps.sty' to locations where LaTeX will find it
