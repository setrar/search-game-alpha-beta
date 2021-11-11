# Interactive 

- [ ] Using the interactive parameter to generate the `.cabal` project file

```
% cabal init --interactive
Should I generate a simple project with sensible defaults? [default: y] n
What does the package build:
   1) Executable
   2) Library
   3) Library and Executable
Your choice? 3
What is the main module of the executable:
 * 1) Main.hs (does not yet exist, but will be created)
   2) Main.lhs (does not yet exist, but will be created)
   3) Other (specify)
Your choice? [default: Main.hs (does not yet exist, but will be created)] 2
Please choose version of the Cabal specification to use:
   1) 1.10   (legacy)
   2) 2.0    (+ support for Backpack, internal sub-libs, '^>=' operator)
   3) 2.2    (+ support for 'common', 'elif', redundant commas, SPDX)
 * 4) 2.4    (+ support for '**' globbing)
   5) 3.0    (+ set notation for ==, common stanzas in ifs, more redundant commas, better pkgconfig-depends)
Your choice? [default: 2.4    (+ support for '**' globbing)] 5
Package name? [default: search-game-alpha-beta] 
Package version? [default: 0.1.0.0] 
Please choose a license:
 * 1) NONE
   2) BSD-2-Clause
   3) BSD-3-Clause
   4) Apache-2.0
   5) MIT
   6) MPL-2.0
   7) ISC
   8) GPL-2.0-only
   9) GPL-3.0-only
  10) LGPL-2.1-only
  11) LGPL-3.0-only
  12) AGPL-3.0-only
  13) GPL-2.0-or-later
  14) GPL-3.0-or-later
  15) LGPL-2.1-or-later
  16) LGPL-3.0-or-later
  17) AGPL-3.0-or-later
  18) Other (specify)
Your choice? [default: NONE] 14
Author name? [default: setrar] 
Maintainer email? [default: ****ar@*****a.com] 
Project homepage URL? 
Project synopsis? Algorithm Studies : Zero Sum Game - minimax search using Alpha and Beta optimisation through Haskell
Project category:
 * 1) (none)
   2) Codec
   3) Concurrency
   4) Control
   5) Data
   6) Database
   7) Development
   8) Distribution
   9) Game
  10) Graphics
  11) Language
  12) Math
  13) Network
  14) Sound
  15) System
  16) Testing
  17) Text
  18) Web
  19) Other (specify)
Your choice? [default: (none)] 9
Application (Main.lhs) directory:
 * 1) app
   2) src-exe
   3) (none)
   4) Other (specify)
Your choice? [default: app] 
Library source directory:
 * 1) src
   2) lib
   3) src-lib
   4) (none)
   5) Other (specify)
Your choice? [default: src] 
Should I generate a test suite for the library? [default: y] y
Test directory:
 * 1) test
   2) Other (specify)
Your choice? [default: test] 
What base language is the package written in:
 * 1) Haskell2010
   2) Haskell98
   3) Other (specify)
Your choice? [default: Haskell2010] 
Add informative comments to each field in the cabal file (y/n)? [default: n]  

Guessing dependencies...

Generating LICENSE...
Warning: LICENSE already exists, backing up old version in LICENSE.save0
Generating CHANGELOG.md...
Generating src/MyLib.hs...
Generating app/Main.lhs...
Generating test/MyLibTest.hs...
Generating search-game-alpha-beta.cabal...

You may want to edit the .cabal file and add a Description field.
```
