# Assignment-01: Starting a Git Repository

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Start a Git repository for your lab folder and save your work with commits.

---

## 📝 Tasks & Solutions

### Task 1: task-01-git-config.txt
**Problem Statement:**
> Create a folder named html-lab and start a Git repository in it with git init. Set your own name and email for this repository only (git config --local). Then show them with git config user.name and git config user.email.

**Source Code:**
```txt
# Name: Anant Pratap Singh
# Student ID: BCS2025542
# Institution: Invertis University, Bareilly
# Course: B.Tech CSE - Second Year
# Subject: HTML and CSS Introduction Lab (BCS352)
# Assignment: 1 - Starting a Git Repository
# Task: 1

$ mkdir html-lab
$ cd html-lab
$ git init
Initialized empty Git repository in /html-lab/.git/
$ git config --local user.name "Anant Pratap Singh"
$ git config --local user.email "anantpratapsingh@invertis.org"
$ git config user.name
Anant Pratap Singh
$ git config user.email
anantpratapsingh@invertis.org
```

**Output / Result:**
```text
Anant Pratap Singh
anantpratapsingh@invertis.org
```

---
### Task 2: index.html
**Problem Statement:**
> Create index.html inside html-lab with one h1 heading, any text. Run git status, add the file and commit it with the message "Add home page".

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 1 - Starting a Git Repository
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HTML Lab - Home</title>
</head>
<body>
  <h1>Welcome to HTML &amp; CSS Lab</h1>
</body>
</html>
```

**Output / Result:**
```text
git status lists index.html as untracked. After git commit -m "Add home page", 1 file changed, 1 insertion(+).
```

---
### Task 3: task-03-git-log.txt
**Problem Statement:**
> Add a second heading, an h2, below the first one in index.html. Commit it with the message "Add next meeting heading", then run git log --oneline.

**Source Code:**
```txt
# Name: Anant Pratap Singh
# Student ID: BCS2025542
# Institution: Invertis University, Bareilly
# Course: B.Tech CSE - Second Year
# Subject: HTML and CSS Introduction Lab (BCS352)
# Assignment: 1 - Starting a Git Repository
# Task: 3

$ git add index.html
$ git commit -m "Add next meeting heading"
[master a1b2c3d] Add next meeting heading
 1 file changed, 1 insertion(+)

$ git log --oneline
a1b2c3d Add next meeting heading
f4e5d6c Add home page
```

**Output / Result:**
```text
Two commits are listed, newest one first:
a1b2c3d Add next meeting heading
f4e5d6c Add home page
```

---

