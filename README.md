SETUP
Configuring user information used across all local repositories

*git config --global user.name “[firstname lastname]”
set a name that is identifiable for credit when review version history

*git config --global user.email “[valid-email]”
set an email address that will be associated with each history marker

*git config --global color.ui auto
set automatic command line coloring for Git for easy reviewing

SETUP & INIT
Configuring user information, initializing and cloning repositories

*git init
initialize an existing directory as a Git repository

*git clone [url]
retrieve an entire repository from a hosted location via URL

STAGE & SNAPSHOT
Working with snapshots and the Git staging area

*git status
show modified files in working directory, staged for your next commit

*git add [file]
add a file as it looks now to your next commit (stage)

*git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot

SHARE & UPDATE
Retrieving updates from another repository and updating local repos

*git remote add [alias] [url]
add a git URL as an alias

*git fetch [alias]
fetch down all the branches from that Git remote

*git merge [alias]/[branch]
merge a remote branch into your current branch to bring it up to date

*git push [alias] [branch]
Transmit local branch commits to the remote repository branch

*git pull
fetch and merge any commits from the tracking remote branch

