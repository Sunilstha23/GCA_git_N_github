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
|----------|-->commit -m "added in new"(newbranch).
|----------|
|--->git merge newbrench(master).
(master).

------- **for more visulization visit site [visualizing git](http://git-school.github.io/visualizing-git/)**-------

**more terminology**

- to check branch : **git branch**.
- to add branch : **git branch <branch name>**.
- to switch branch : **git checkout <branch name>**.
- to delete branch : **git branch -b <branch name>**.
- to merge branch : **git merge <branch name>**.

- shortcuts to create and switch to branch : **git checkout -b <branch name>**.

---

### DAY 3

---

**Fork, Clone and Pull Request**

- **Fork** : is a copy of a repository in your own github account
- **Clone** : is to download the file/code in your desktop
- **pull request** : is a request to tell a remote user to pull the changes

**How it's work**

For Fork :

- go to remote repository which you need to access to your repository.
- then right size of the name of repository you got to see a Fork.
- click Fork and it's appear to your repository.

for clone which is Fork from remote:

- you got to see a green color button with code and download signal.
- click button and copy the url of that.
- open git bash and write "git clone (url of repository)".
- and then you can make change.

**remote url after fork**

- to check url name: **git remote -v**
- to add remote url name in your repository: **git remote add upsteam (url of remote repository)**.
  - this helps us to pull the change done by the remote repository after fork also if this is not done then we cann't.

for pull request:

- taking hover towards pull request and click it
- after clicking it you can see a pull request on green button
- pull request(click)--> create pull request(click)
- write title and message of request by summiting pull request

---
