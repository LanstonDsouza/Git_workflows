GIT ADD
The git add command adds new or changed files in your working directory to the Git staging area.
Git add is an important command - without it, no git commit would ever do anything.
As you're working, you change and save a file, or multiple files. Then, before you commit, you must git add.
The git add and git commit go together hand in hand. They don't work when they aren't used together. And, they both work best when used thinking of their joint functionality
Git add [filename] selects that file, and moves it to the staging area, marking it for inclusion in the next commit. You can select all files, a directory, specific files, or even specific parts of a file for staging and commit.
Uses of ADD
Git add .  : Stage all files (that are not listed in the .gitignore) in the entire repository.
git add -A: stages all files, including new, modified, and deleted files, including files in the current directory and in higher directories that still belong to the same git repository
git add .: adds the entire directory recursively, including files whose names begin with a dot
git add -u: stages new and modified files only, NOT deleted files