# Version Control

## Week 1

### Introduction

- vc is a way to keep records of all changes to files
- centralized vs distributed
- diff and blame

### How do developers collaborate in the real world?

- communication - key to collaboration
- learning to estimate is critical

### A history of version control

VCS (Version Control Systems)
- manage changes to the code
- track who made each change
- goes back to the 1980s

History
- CVS (Concurrent Versions System)
- SVN (Subversion)
- Mercurial and Git

CVS
- 1986, Walter F. Tichy, Purdue Univ
- centralized
- stores info about every file in a folder structure
    - name, location, last modified by/when
- stores info about folders
- cons:
    - no integrity checks (ie. data can become corrupted)
    - if errors, system accepts partial or corrupted files
    - designed for text files

SVN
- Collabnet, 2000
- solved many issues with CVS
    - included integrity checks
    - supported versioning of binary files
- cons:
    - centralized
        - if server down/slow, development is affected

Mercurial
- 2005 start, Olivia Mackall
- high-perf VCS
- distributed CVS
- easy for SVN to transition to it
- small learning curve

Git
- 2005 start, Linus Torvalds
- 2007 first public release
- became popular in the OS community

### VC in professional software development

VC is complemented by other tools/process

Workflow
- a process to determine how to handle conflicts
- ensures code is managed and reduced mistakes from happening
- includes peer review system

CI (Continuous Integration)
- automates integration of code changes
- automatically compiles project and runs test on every code change
- goals:
    - build remains stable
    - prevent regression in functionality

Continuous Delivery
- ext of CI
- automatically packages the application and preps it for deployment
- helps avoid human error when packaging the application

Continuous Deployment
- extension of Continuous Delivery
- goals:
    - release/deploy to customers safely and frequently
- sandbox/staging site before live/prod site
    - use sandbox to validate deployment and changes

### Staging vs. Prod

Staging/Sandbox
- should mimic prod
- test the code in an env that matches what you have in prod
- the time to find potential issues before going live
- areas that benefits:
    - new features
    - testing
        - unit, integration, performance
    - migrations
    - configuration changes

Prod/Live
- issues should have been caught during staging
- downtime impacts revenue
- vulnerabilities
    - cybersecurity should play a big role in what gets released to prod
    - updates (ie. patching, upgrading versions) should be checked/verified
    - also test if not upgrading software when critical updates are released
- issues in prod is damaging; does not install confidence in users

### Additional Resources

[About Version Control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

[List of Version Control Software](https://en.wikipedia.org/wiki/List_of_version-control_software)

[The benefits of a distributed version control system](https://about.gitlab.com/topics/version-control/benefits-distributed-version-control-system/)

[What is Cloning?](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)

## Week 2

### The Command Line

- benefits
    - automating tasks
    - improved performace vs GUI
    - interacting with cloud provider platforms in a consistent way

### Bash on Mac

Most common commands

| Command | Used for |
| --- | --- |
| cd | Change Directory |
| ls | List command used for showing the content of a directory. |
| rm | Remove command used for removing a file or a directory |
| mv | Used to move files or folders to another location |
| touch | Allows creating of a new empty file or to update a timestamp on a file |
| cp | Used to make a copy of a file or folder |
| mkdir | Make a new directory |
| pwd | Print work directory, shows the current location in the shell |
| cat | Allows reading or concatenation of a file |
| less | Displays the contents of a file one page at a time. |
| grep | Global regular expression, allows for searching contents of files or folders |

Flags
- every command has flag to change the output of the command itself
- `ls` prints out contents inside a directory
- `ls -` does the same, but in a list view

Man pages
- every command has its manual
- lists all the flags and options that a particular command has to offer
- ie. `man ls`

### Unix commands

`uniq`
- filters adjacent matching lines

### Pipes, redirection, and grep

Pipes
- combine commands together
- pass output of one command as input into another command

Redirection
| Standard Input | Standard Output | Standard Error |
| --- | --- | --- |
| 0 | 1 | 2 |
| < | > | 2> or 2>&1 |

Grep (global regular expression)
- `grep Sam names.txt` searches for names in the file with Sam
- flags are options to modify the command
    - `-i` to make case-insensitive
    - `-w` for exact match
- use pipes to string commands together
    `ls /bin | grep zip` looks for folders that include the word zip in the name

### Additional Resources

[Agile methodologies](https://www.planview.com/resources/guide/agile-methodologies-a-beginners-guide/)

[Installing git on mac and windows, detailed instructions.](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

[Bash Reference Manual](https://www.gnu.org/software/bash/manual/html_node/index.html#SEC_Contents)

[Bash Redirections](https://www.gnu.org/software/bash/manual/html_node/Redirections.html#Redirections)

[Bash Cheatsheet](https://devhints.io/bash)

[Grep Cheatsheet](https://devhints.io/grep)

[Grep Manual](https://man7.org/linux/man-pages/man1/grep.1.html)

[History and Timeline of Unix](https://unix.org/what_is_unix/history_timeline.html)

[History of Vim](https://en.wikipedia.org/wiki/Vim_(text_editor))

[How to work with relative and absolute paths](https://www.geeksforgeeks.org/absolute-relative-pathnames-unix/)

[Unix Commands Cheatsheet](https://cheatography.com/jluis/cheat-sheets/bash-and-unix-commands/)

[Vim Cheatsheet](https://vim.rtorr.com/[)

## Week 3

### Git and GitHub

#### Remote vs Local
- local - your working directory
- remote
    - any other remote repository to which developers can push changes
    - can be a centralized repo

#### Branching

```
git branch branchName
git checkout -b branchName
```

#### Additional Resources

[Git: An Origin Story](https://www.linuxjournal.com/content/git-origin-story)

[Git Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)

[Git patterns and anti-patterns for successful developers](https://youtu.be/t_4lLR6F_yk)

[Tech Talk: Linus Torvalds on git](https://www.youtube.com/watch?v=4XpnKHJAok8)

[Vim Cheatsheet](https://devhints.io/vim)
