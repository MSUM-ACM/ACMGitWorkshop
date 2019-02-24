# Showing the working tree status

This directory is for the introduction and instructions for showing the status of the working tree.

Initial Instructions *(02-06-2019)*
-

1. Open a terminal
2. Navigate to a git initialized directory
3. Add a file and add content to it
4. Type in `git status`

This command displays two sections of files. The first section is the differences between the git index and the current HEAD commit, this section will show what you *would* commit by using the git commit command. The second section is the differences between the working tree and the git index, and differences that are untracked, this section will show what you *could* commit by executing git add before using git commit.
