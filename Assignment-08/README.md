# Assignment-08: Sign-Up Forms and Choices

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Make a labelled form with text, email and password fields, choices and a submit button.

---

## 📝 Tasks & Solutions

### Task 1: signup.html
**Problem Statement:**
> Create signup.html with a form (method post, action thanks.html; you do not need to create thanks.html). Add labelled fields for full name, email and password. Each label must be linked to its field.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 8 - Sign-Up Forms and Choices
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sign Up Form</title>
</head>
<body>
  <h1>Student Registration</h1>
  <form method="post" action="thanks.html">
    <div>
      <label for="fullName">Full Name:</label>
      <input type="text" id="fullName" name="fullName">
    </div><br>

    <div>
      <label for="userEmail">Email:</label>
      <input type="email" id="userEmail" name="userEmail">
    </div><br>

    <div>
      <label for="userPassword">Password:</label>
      <input type="password" id="userPassword" name="userPassword">
    </div><br>

    <button type="submit">Sign Up</button>
  </form>
</body>
</html>
```

**Output / Result:**
```text
Three properly bound input fields: text, email, and masked password.
```

---
### Task 2: choices.html
**Problem Statement:**
> Create choices.html with a gender question using two radio buttons, Female and Male, and a course dropdown with the options BCA and B.Tech.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 8 - Sign-Up Forms and Choices
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Choices &amp; Selections</title>
</head>
<body>
  <h2>Select Your Options</h2>
  <form>
    <p>Gender:</p>
    <input type="radio" id="genderFemale" name="gender" value="female">
    <label for="genderFemale">Female</label>

    <input type="radio" id="genderMale" name="gender" value="male">
    <label for="genderMale">Male</label><br><br>

    <label for="courseSelect">Choose Course:</label>
    <select id="courseSelect" name="course">
      <option value="bca">BCA</option>
      <option value="btech">B.Tech</option>
    </select>
  </form>
</body>
</html>
```

**Output / Result:**
```text
Mutually exclusive gender radio buttons and course selection dropdown.
```

---
### Task 3: signup-required.html
**Problem Statement:**
> Create signup-required.html with a full name field and an email field. Make both required, add a placeholder to the name field, and add a Submit button.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 8 - Sign-Up Forms and Choices
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Required Sign Up</title>
</head>
<body>
  <h2>Sign Up (Validated)</h2>
  <form method="post" action="thanks.html">
    <div>
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your full name" required>
    </div><br>

    <div>
      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" required>
    </div><br>

    <button type="submit">Submit</button>
  </form>
</body>
</html>
```

**Output / Result:**
```text
Browser validation triggers if either required field is submitted blank.
```

---

