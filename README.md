# phase-0-gps-1

333  git clone https://github.com/Dyoon3102/phase-0-gps-1.git
*Cloning the repository from GitHub to local
  334  ls
  *listing contents of current folder
  337  ls -a
  *listing contents of current folder in detail
  339  cd phase-0-gps-1
  *change directory to specified
  340  ls -la
  341  touch awesome_page.md
  *create file
  342  ls
  345  git add awesome_page.md
  *stage the file for commit
  346  git status
  *check the status of the content
  347  git commit -m "Create and add awesome_page.md"
  *saving the changes of the content to the repository with comment
  348  git status
  349  git push origin master
  *push the file to the master branch
  350  git branch
  *check current branch
  351  git checkout -b add-command-log
  *create and change to a feature branch
  352  git branch
  353  ls
  354  open readme.md
  *open file