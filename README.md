# test-keywords-git
keyword expansion testing

Some of my (pro and personal) workflows need keywords expansion (à la svn). 

I want to test some solutions here.

## basic method

simply add the actual hash of the commit into $Id: README.md 1.1 $

https://git-scm.com/book/en/v2/Customizing-Git-Git-Attributes

## rcs/svn behavior

use gaIdke (Automatic GIT Id Keyword Expansion, perl and bash)

http://www.immediatec.net/2016/09/07/git-correct-id-keyword-expansion/
https://github.com/JohnWulff/immediatec

## hybrid and other behaviors

https://softwareengineering.stackexchange.com/questions/141973/how-do-you-achieve-a-numeric-versioning-scheme-with-git

x.y.<number of commits>.r<git-hash> ?

https://github.com/BradleyA/markit ?


