1) Run git log to see the commits you have already made.

```
> git log
commit 1be07bb4de065191f27633489c68a7966719281b (HEAD -> master, origin/master, origin/HEAD)
Author: kilroy396 <andrew@boistout.net>
Date:   Mon Jul 24 16:47:39 2017 +1000

    renamed keeping-your-changes-under-control.md

commit 8707970cabc583fc7427a7378ffc47af24b430a3
Author: kilroy396 <andrew@boistout.net>
Date:   Mon Jul 24 13:07:21 2017 +1000

    updated .gitignore

commit 10d4ebef7eb1b70731f20c83055bc203c2fda87f
Author: kilroy396 <andrew@boistout.net>
Date:   Mon Jul 24 12:32:07 2017 +1000

    modified gitignore

commit ad5791e0aa63f9e02a437d791ac8ce5780212542
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 17:52:49 2017 +1000

    assignment git-status

commit f51b24fb46e0639c55e26191ec5ef30cd410335a
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 13:39:05 2017 +1000

    changed .gitignore and removed some files

commit a0d5972372697b238d03d97d4b086c519e349f3d
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 12:32:33 2017 +1000

    modified .gitignore

commit f7ad3f829238461820cdf7695dd0ce9660870484
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 12:29:03 2017 +1000

    created a PDF and powerpoint from the mindmap

commit 3cb511e45d65f2d6a91c64b79c03c11e8f4e3e0e
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 11:42:28 2017 +1000

    Upadted mindmap

commit 42620174b152463f8f96709e708ceae7ff616a7e
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 11:30:49 2017 +1000

    Upadted mindmap

commit 7621336d82cc43534ca5efb8f4415e3f561157f0
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 11:11:07 2017 +1000

    added README.md

commit 30e82da40b27cad7467c617be2875b69335e22c6
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 11:09:10 2017 +1000

    added .gitignore
```

2) Try the command again with the --stat switch to get information about which files were affected in each commit

```
> git log --stat
commit 1be07bb4de065191f27633489c68a7966719281b (HEAD -> master, origin/master, origin/HEAD)
Author: kilroy396 <andrew@boistout.net>
Date:   Mon Jul 24 16:47:39 2017 +1000

    renamed keeping-your-changes-under-control.md

 assignments/keeping-your-changes-under-control.md | 34 +++++++++++++++++++++++
 1 file changed, 34 insertions(+)

commit 8707970cabc583fc7427a7378ffc47af24b430a3
Author: kilroy396 <andrew@boistout.net>
Date:   Mon Jul 24 13:07:21 2017 +1000

    updated .gitignore

 .gitignore | 2 --
 1 file changed, 2 deletions(-)

commit 10d4ebef7eb1b70731f20c83055bc203c2fda87f
Author: kilroy396 <andrew@boistout.net>
Date:   Mon Jul 24 12:32:07 2017 +1000

    modified gitignore

 .gitignore | 1 +
 1 file changed, 1 insertion(+)

commit ad5791e0aa63f9e02a437d791ac8ce5780212542
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 17:52:49 2017 +1000

    assignment git-status

 assignments/assignment-git_status | 6 ++++++
 1 file changed, 6 insertions(+)

commit f51b24fb46e0639c55e26191ec5ef30cd410335a
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 13:39:05 2017 +1000

    changed .gitignore and removed some files

 .gitignore                     |     7 +-
 Getting Started with GIT.pdf   | 43171 ---------------------------------------
 Getting Started with GIT.ppt   |   Bin 247296 -> 0 bytes
 Getting Started with GIT.xmind |   Bin 189854 -> 0 bytes
 4 files changed, 5 insertions(+), 43173 deletions(-)

commit a0d5972372697b238d03d97d4b086c519e349f3d
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 12:32:33 2017 +1000

    modified .gitignore

 .gitignore | 2 ++
 1 file changed, 2 insertions(+)

commit f7ad3f829238461820cdf7695dd0ce9660870484
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 12:29:03 2017 +1000

    created a PDF and powerpoint from the mindmap

 GIT plan.pdf                   |   Bin 25326 -> 0 bytes
 GIT plan.xmind                 |   Bin 123789 -> 0 bytes
 Getting Started with GIT.pdf   | 43171 +++++++++++++++++++++++++++++++++++++++
 Getting Started with GIT.ppt   |   Bin 0 -> 247296 bytes
 Getting Started with GIT.xmind |   Bin 0 -> 189854 bytes
 5 files changed, 43171 insertions(+)

commit 3cb511e45d65f2d6a91c64b79c03c11e8f4e3e0e
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 11:42:28 2017 +1000

    Upadted mindmap

 GIT plan.xmind | Bin 92540 -> 123789 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)

commit 42620174b152463f8f96709e708ceae7ff616a7e
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 11:30:49 2017 +1000

    Upadted mindmap

 GIT plan.xmind | Bin 32811 -> 92540 bytes
 1 file changed, 0 insertions(+), 0 deletions(-)

commit 7621336d82cc43534ca5efb8f4415e3f561157f0
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 11:11:07 2017 +1000

    added README.md

 README.md | 1 +
 1 file changed, 1 insertion(+)

commit 30e82da40b27cad7467c617be2875b69335e22c6
Author: kilroy396 <andrew@boistout.net>
Date:   Fri Jul 21 11:09:10 2017 +1000

    added .gitignore

 .gitignore     |   1 +
 GIT plan.pdf   | Bin 0 -> 25326 bytes
 GIT plan.xmind | Bin 0 -> 32811 bytes
 accompaniments |   1 +
 bisect-example |   1 +
 5 files changed, 3 insertions(+)
```

3) For a compact view, use git log --oneline - this is useful when looking at a bigger picture

```
> git log --oneline
1be07bb (HEAD -> master, origin/master, origin/HEAD) renamed keeping-your-changes-under-control.md
8707970 updated .gitignore
10d4ebe modified gitignore
ad5791e assignment git-status
f51b24f changed .gitignore and removed some files
a0d5972 modified .gitignore
f7ad3f8 created a PDF and powerpoint from the mindmap
3cb511e Upadted mindmap
4262017 Upadted mindmap
7621336 added README.md
30e82da added .gitignore
```