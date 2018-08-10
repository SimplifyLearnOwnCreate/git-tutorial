# git-tutorial


## Reset local repo to be remote HEAD
$ git fetch origin<br>
$ git reset --hard origin/master<br>


## 1: Add to staged files
Single file         $ git add path<br>
More than 1 file 	  $	git add path1 path2<br>
All files			      $ git add -A<br>

## 1: Discard non-staged changes

Single file   $ git checkout path<br>
All files     $ git checkout -- .<br>

## 2: commit staged files
Single file 	      $	git commit path -m “message”<br>
More than 1 file 	  $	git commit path1 path2 -m “message”<br>
All files           $	git commit -am “message”<br>

## 2: Discard staged changes

Single file   $ git reset HEAD path<br>
All files     $ git reset HEAD *<br>

## 3: Update remote with local commits
update remote with commit(s)  $	git push<br>
