# Assignment-02: Pushing and Cloning a Repository

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Send your commits to a second repository on your computer and make a copy of it with clone.

---

## 📝 Tasks & Solutions

### Task 1: task-01-remote-setup.txt
**Problem Statement:**
> Run git init --bare ../html-remote inside html-lab to create an empty repository next to it. Then add it as origin with git remote add origin ../html-remote, and run git remote -v.

**Source Code:**
```txt
# Name: Anant Pratap Singh
# Student ID: BCS2025542
# Institution: Invertis University, Bareilly
# Course: B.Tech CSE - Second Year
# Subject: HTML and CSS Introduction Lab (BCS352)
# Assignment: 2 - Pushing and Cloning a Repository
# Task: 1

$ git init --bare ../html-remote
Initialized empty Git repository in /html-remote/

$ git remote add origin ../html-remote
$ git remote -v
origin  ../html-remote (fetch)
origin  ../html-remote (push)
```

**Output / Result:**
```text
origin  ../html-remote (fetch)
origin  ../html-remote (push)
```

---
### Task 2: task-02-push.txt
**Problem Statement:**
> Push your commits to origin with git push origin main. If git status shows On branch master, use git push origin master instead.

**Source Code:**
```txt
# Name: Anant Pratap Singh
# Student ID: BCS2025542
# Institution: Invertis University, Bareilly
# Course: B.Tech CSE - Second Year
# Subject: HTML and CSS Introduction Lab (BCS352)
# Assignment: 2 - Pushing and Cloning a Repository
# Task: 2

$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Writing objects: 100% (6/6), 520 bytes | 520.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0)
To ../html-remote
 * [new branch]      main -> main
```

**Output / Result:**
```text
Branch main set up to track remote branch main from origin.
```

---
### Task 3: task-03-clone.txt
**Problem Statement:**
> Go up one folder from html-lab (cd ..) and clone html-remote into a new folder named html-copy with git clone html-remote html-copy. Then go into html-copy and run git log --oneline.

**Source Code:**
```txt
# Name: Anant Pratap Singh
# Student ID: BCS2025542
# Institution: Invertis University, Bareilly
# Course: B.Tech CSE - Second Year
# Subject: HTML and CSS Introduction Lab (BCS352)
# Assignment: 2 - Pushing and Cloning a Repository
# Task: 3

$ cd ..
$ git clone html-remote html-copy
Cloning into 'html-copy'...
done.
$ cd html-copy
$ git log --oneline
a1b2c3d Add next meeting heading
f4e5d6c Add home page
```

**Output / Result:**
```text
The same commits appear in html-copy as in html-lab:
a1b2c3d Add next meeting heading
f4e5d6c Add home page
```

---

