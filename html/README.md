
In order to change to a new director we should use the command:
- cd

View current directory content:
- ls

Clean up UI 
- clear

Navigate to parent directory
- cd ..

Create a new Directory
- mkdir directory_name

Create a new file
- touch file_name.extension

Enter insert mode in vim
- press i

Exit insert mode in vim
- Esc

Exit vim when there are no changes made to the file
- :q

Exit vim with saved changes
- :wq

Exit vim without saving changes
- :q!

Deleting files
- rm file_name

Delete directory
- rm -r

Preview the contents of a file
- cat file_name

Show current path (working directory path)
- pwd

Path types:

- Absolute path:

 C:/users/wili/documents

- Relative path:

1. ..
2. directory_name or ./directory_name

Root relative path /

rm -rf /

List everything from a directory including hidden files and details
- ls -la or ll

Creating aliases for short commands (These have to be added to .bashrc)
- alias ll="ls -la"

In order to get documentation for a command we can use

- man ls (Linux/Mac)
- ls --help

VS Code

- Open Command palette (Pentru a executa comenzi in vs code) F1 or shift + ctrl + p

Git

1. Add changes from Work directory to Staging area
- git add file_name
- git add path_to_file/file_name
- git add . (Adds every change to staging area)

2. Storing changes in Git (Commit)
- git commit -m"descriptive commit message about the changes"

3. Checking the current status of the changes
- git status

4. Seeing a list of the commits on a branch
- git log

5. Reset changes from staging area
- git reset (Resets all changes)
- git reset file_name or file_path/filename (for a single change)

6. Undoing last commit (Be sure to check firs where the HEAD is placed in the commit chain, should be on the last commit)
- git reset HEAD~1

Linking local repository to online repository:
- git remote add origin online_repository_url

Synchronize changes from local to remote 
- git push

In order to retrieve the latest changes from a git repository
- git pull

In order to create a new branch
- git checkout -b branch_name
- git switch -c branch_name

In order to navigate (checkout) to an existing branch
- git checkout branch_name
- git switch branch_name

In order to see all the branches (and also check the current branch that we're on)
- git branch

In order to delete a branch
- git branch -D branch_name

My name is Wili
Hello world

# Heading
## Heading
### Heading

| Syntax | Description | Title |
| --- | ----------- | -- |
| Header | Title | Hello world |
| Paragraph | Text | siit 36 |
