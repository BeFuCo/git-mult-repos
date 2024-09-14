# Developing with Feature-Branches, multiple remotes 

## Setup GIT project on local computer
1. Create project folder, e.g. `git-mult-repos`
2. Switch to this project folder
  - `$ git init`
  - `$ git status` shows `...git-mult-repos (master)`
  - Create on branch <span style="color:blue">master</span> the files 
    - `README.md` 
    - `LICENSE.md`
  - 
3. Files `README.md` und `LICENSE.md` in lokalem GIT-repository speichern
  - `$ git status`
    `On branch master`
    `No commits yet`
    ````
    Untracked files
      (use "git add <file>..." to include in what will be committed)
        LICENSE.md
        README.md
    ````
    `nothing added to commit but untracked files present (use "git add" to track)`

  - `$ git add .`
      `````
      $ git commit -m "init with README.md LICENSE.md"
      [master (root-commit) 57759ac] init with README.md LICENSE.md
      2 files changed, 80 insertions(+)
      create mode 100644 LICENSE.md
      create mode 100644 README.md
      `````

