# test-keywords-git
keyword expansion testing

this one will change each commit, the other one will not.

$Id: README.md 1.3 $

$IdBlockFurtherExpansion$

Some of my (pro and personal) workflows need keywords expansion (à la svn). 

I want to test some solutions here.

## rcs/svn behavior

use gaIdke (Automatic GIT Id Keyword Expansion, perl and bash)

http://www.immediatec.net/2016/09/07/git-correct-id-keyword-expansion/
https://github.com/JohnWulff/immediatec

Ongoing tests: It fits the needs.

## basic Git method

simply add the actual hash of the commit into $Id$

https://git-scm.com/book/en/v2/Customizing-Git-Git-Attributes

Need to much customizing.

## hybrid and other behaviors

https://softwareengineering.stackexchange.com/questions/141973/how-do-you-achieve-a-numeric-versioning-scheme-with-git

x.y.<number of commits>.r<git-hash> ?

https://github.com/BradleyA/markit ?

Already done by gaIdke.

