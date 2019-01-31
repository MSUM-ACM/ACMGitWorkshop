# Adding file contents to the index

This directory is for the introduction and instructions for adding file contents to the Git index.

Initial Instructions *(01-29-2019)*
-

1. Open a terminal
2. Navigate to a git initialized directory
3. Add a file and add content to it
4. Type in `git add *`

This adds the file contents to the git index, a snapshot of the content of the working tree. `git add` can be performed multiple times before a commit, however, only the contents of the files at the time the `add` command is executed are added. This command is most commonly used with `git status` to display a summary of content that has or has not been staged for the next commit.
