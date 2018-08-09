# git-tutorial

## Discard unstage changes

-Single file     $ git checkout path<br>
-All files       $ git checkout -- .<br>

## Discard staged changes

Single file     $ git reset HEAD path<br>
All files       $ git reset HEAD *<br>

## Reset local repo to be remote HEAD 
$ git fetch origin<br>
$ git reset --hard origin/master<br>
