Answer 1: git version 2.39.3 (Apple Git-146)

Answer 2: credential.helper=osxkeychain
init.defaultbranch=main
user.name=TreWilson
user.email=Tw340223@ohio.edu
credential.helper=cache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
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
core.ignorecase=true
core.precomposeunicode=true
remote.origin.url=https://github.com/TreWilson/git-lab.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main

Answer 3: GIT-ADD(1)                     Git Manual                    GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--intera
ctive | -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--u
pdate | -u]] [--sparse]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--
ignore-missing] [--renormalize]
                 [--chmod=(+|-)x] [--pathspec-from-file=<file> [--pathspe
c-file-nul]]
                 [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found
       in the working tree, to prepare the content staged for the next
       commit. It typically adds the current content of existing paths
       as a whole, but with some options it can also be used to add
       content with only part of the changes made to the working tree
       files applied, or remove paths that do not exist in the working
       tree anymore.

       The "index" holds a snapshot of the content of the working tree,
       and it is this snapshot that is taken as the contents of the
       next commit. Thus after making any changes to the working tree,
       and before running the commit command, you must use the add
       command to add any new or modified files to the index.

Answer 4:On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)

answer 5:trewilson@Tres-Air git-lab % git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

answer 6: trewilson@Tres-Air git-lab % git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

answer 7: trewilson@Tres-Air git-lab % git status
On branch main
nothing to commit, working tree clean

answer 8: commit 2563a33821ef751fb243a35ad3600f9bd63fe882 (HEAD -> main)
Author: TreWilson <Tw340223@ohio.edu>
Date:   Fri May 17 14:05:09 2024 -0400

    Initial commit

Answer 9: git remote add origin https://github.com/TreWilson/git-lab.git
git push -u origin main
error: remote origin already exists.
git: 'credential-cache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' is not a git command. See 'git --help'.
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 225 bytes | 225.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/TreWilson/git-lab.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Answer 10: No

Answer 11: git: 'credential-cache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' is not a git command. See 'git --help'.
To https://github.com/TreWilson/git-lab.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/TreWilson/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12: no

Answer 13: .               .git            answers.md
..              README.md       git-lab-2
