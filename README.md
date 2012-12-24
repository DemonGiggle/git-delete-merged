git delete-merged
=================

Remove merged local l&amp; remote branches
Note that we only care those branches with the prefix: feature/ or bugfix/

__INSTALL__

1. copy git-delete-merge to any place specified in $PATH
2. chmod +x git-delete-merge

__EXAMPLE__

Assume you want to delete the local brances which are merged into master

1. git checkout master
2. git delete-merge

If you want to delete remote branches also:

1. git checkout master
2. git delete-merge -r
