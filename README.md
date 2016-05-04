# git_mkdir

A simple bash script for OS X. It is for creating a new local git project repository.

## Usage

#### 1. Place the file `git_mkdir` in `/usr/local/bin` so that the git_mkdir command will be available globally.
- [How to make a shell script global?](http://stackoverflow.com/questions/3560326/how-to-make-a-shell-script-global)

#### 2. In a terminal, run `git_mkdir` and enter your desired name for a new project.

```bash
$ git_mkdir
Enter the directory name to be created:
git_mkdir
Moving into /Users/masa/git_mkdir
Initialized empty Git repository in /Users/masa/git_mkdir/.git/
[master (root-commit) 3225a39] Initial commit
 3 files changed, 2 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 index.html
total 16
-rw-r--r--    1 masa  staff     0B May  3 21:07 index.html
-rw-r--r--    1 masa  staff    12B May  3 21:07 README.md
-rw-r--r--    1 masa  staff    10B May  3 21:07 .gitignore
drwxr-xr-x   13 masa  staff   442B May  3 21:07 .git
drwxr-xr-x+ 102 masa  staff   3.4K May  3 21:07 ..
drwxr-xr-x    6 masa  staff   204B May  3 21:07 .
Done!
```
