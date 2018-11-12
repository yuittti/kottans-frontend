# Kottans Frontend course
https://github.com/kottans/frontend

### Remote Phase

#### 1. Git and GitHub
(https://github.com/kottans/frontend/blob/master/tasks/git-intro.md)

Good basics of using Git and GitHub, but mostly nothing new for me, as I had an experience with Git before.
But couple of things were quite new and might be useful:
- `git log --stat` to see in the log which files were changed
- `git log --graph --oneline` for the short log 
- use 'q' key to exit git log and git diff (instead of Ctrl + Z)
- forking the repositories

#### 2. Linux, Command Line, HTTP Tools
(https://github.com/kottans/frontend/blob/master/tasks/linux-cli-http.md)

## Linux CLI, and HTTP

Command line complete status

![Command line complete status](https://github.com/yuittti/kottans-frontend/blob/master/task_linux_cli/linux-cli-status.png)

#### Learn command line
I like such interactive courses were you are receiving the knowledges and you are practicing in the same time and you are remembering information by repeating simple things many times. I didn't expect to see in this course the new things, but I was surprised that I found some. I am not sure if I will use all of them often in future, but some of them seems to be pretty useful. So for me the information below was definetly new:
- options for `ls` command, especially `-t` for sorting by date
- using the `mv` command for renaming files
- `cat` with `>>` to add content to existing file
- the pipes `|` for combining different commands
- command `sort`
- command `uniq` to filter duplicated lines in the output
- command `sed` for replacing strings in the output
- command `history` to list the terminal history
- command `grep` - it wasn't new at all for me, but the shown way of its using is interesting as well

#### HTTP
Both articles are very informative. This is a really well structured information about basics knowledge of how does the HTTP protocol works under the hood. 

I liked the thesis 
> *HTTP is an application layer protocol over TCP, which is over IP* 

which does explain a lot about communication between server and client. 

Also it was nice to read in one place all the information about:
- types of existing requests, 
- responses status codes, 
- types of request and response headers

The most interesting part of 2nd article was about basics of identification and authentication processes, but would be nice to dive deeper in this part.

#### 3. Git for Team Collaboration
(https://github.com/kottans/frontend/blob/master/tasks/git-collaboration.md)

## Git Collaboration

![What is Version Control](https://github.com/yuittti/kottans-frontend/blob/master/task_git_collaboration/version-control.png)

![GitHub & Collaboration](https://github.com/yuittti/kottans-frontend/blob/master/task_git_collaboration/github-collaboration.png)

- I liked an explanation what each git command do and how each git command works under the hood.
- This is not about git, by the set of command `mkdir test && cd $_` is very useful not to type 2 commands separately.
- The `git log -p` to display the actual changes made to a file
- It was interesting to read about _Reset vs Revert_ as Reverting creates a new commit that reverts or undos a previous commit. Resetting, on the other hand, erases commits!
- Usefull information about `git fetch` vs `git pull`. Git fetch is used to retrieve commits from a remote repository's branch but it does not automatically merge the local branch with the remote tracking branch after those commits have been received. And git pull is doing fetch and then merge.
- Never used `git log --grep` to filter the commits by the commit message
