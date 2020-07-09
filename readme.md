# Training on GIT AND GITHUB

### PROFILE

---

Hello Everyone!, it's me Sunil Shrestha. Currently pursuing my Bachelor degree on Software engineering and joyful to be part of this placement training organized by GCA and Girl in Tech.

---

### DAY 1

---

**Git and GitHub**

- Git(2008) is maintained and installed on local system where GitHub is exclusively cloud-based(server).

**Git Workflow**

git init -------->WORKING DIRECTORY-------->git add ------->STAGING AREA-------->git commit----->REPOSITORY.
... ... (Additions, Deletion, Modifications) ... (Files are ready for commit) ... (change are saved to repo)

**Some Bash Script**

- _mkdir_ : to make directory.
- _cd_ : Change directory.
- _ls_ : list directory.
- _file_ to create.
  1. _touch_ : create file.
  1. _echo_ : with message create file.
  1. _nano_ : with edit txt and create file.
- rm -R : Remove Files and directory.

**Git Terminology**

- **add** : add files and folder to staging.
- **commit** : create version/snapshot of repo.
- **push** : send files to remote.
- **fetch** : retrieve update information from remote.
- **pull**: retrieve updates from remote.
- **branch**: different section on same repository.
- **clone**: copy your repository.
- **fork**: copy other’s repo into your personal repo.

---

### DAY 2

---

**More Git Command**

- **log** : track all command log.
- eg : git log. +**dif** / diff --staged: Find the different between the staging and working directory.
- eg : git diff.

**branch in git**

1(master)--> commit -m "first"-->2(master)-->git branch newbranch.

<pre><pre><pre><pre><pre><pre>|<pre><pre>|-->commit -m "added in new"(newbranch).
<pre><pre><pre><pre><pre><pre>|----------|
<pre><pre><pre><pre><pre><pre><pre>|--->git merge newbrench(master).
<pre><pre><pre><pre><pre><pre><pre>|(master).

------- **for more visulization visit site [visualizing git](http://git-school.github.io/visualizing-git/)**-------

**more terminology**

- to check branch : **git branch**.
- to add branch : **git branch <branch name>**.
- to switch branch : **git checkout <branch name>**.
- to delete branch : **git branch -b <branch name>**.
- to merge branch : **git merge <branch name>**.

- shortcuts to create and switch to branch : **git checkout -b <branch name>**.

---
