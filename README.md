PuzzleScript
============

Open Source HTML5 Puzzle Game Engine

Try it out at https://www.puzzlescript.net

-----

Dev instructions here - https://groups.google.com/forum/#!searchin/puzzlescript/development/puzzlescript/yptIpY9hlng/cjfrOPy_4jcJ

-----

The MIT License (MIT)

Copyright (c) 2013 increpare

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Patrick notes
-----

    git subtree push --prefix src origin gh-pages

    pancelor — 06/08/2021
    how'd you get github pages to host the src directory? I thought there were only 2 options: the root directory or a docs directory. edit: ah, or a separate branch... are you doing something clever to mirror master -- ./src as gh-pages -- ., or are you doing it manually?
    Menderbug — 06/08/2021
    git subtree push --prefix src origin gh-pages
    that makes the gh-pages branch essentially just point at the src subfolder
    so the index.html is at the root of gh-pages
    Menderbug — 06/08/2021
    Ah, but I'm not sure if it's automatic. I think I'll probably have to run that command each time I make changes
    Still more convenient than changing the repo structure
    clementsparrow — 06/08/2021
    you could use GitHub's APIs to make it automatically, but it's probably too much work
    Menderbug — 06/08/2021
    I could probably drop the command in a post-commit hook or something
    I'll worry about that if I end up making lots of changes to this fork
    there's some audio-related things I want to tweak, but I don't have any other plans for it at the moment
