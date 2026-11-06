# Assignment-04: Divs, Attributes and a Small Fix

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Group parts of a page with div elements, add a data attribute, and fix the errors in a broken page.

---

## 📝 Tasks & Solutions

### Task 1: layout.html
**Problem Statement:**
> Create layout.html with three div blocks: one with the class header, one with the class main and one with the class footer. Put some text in each.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 4 - Divs, Attributes and a Small Fix
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Page Layout with Divs</title>
</head>
<body>
  <div class="header">
    <h2>Website Header Section</h2>
  </div>

  <div class="main">
    <p>This is the main content area where articles and primary information are displayed.</p>
  </div>

  <div class="footer">
    <p>&copy; 2026 Invertis University - All Rights Reserved.</p>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Renders three stacked division blocks: header, main, and footer.
```

---
### Task 2: attributes.html
**Problem Statement:**
> Create attributes.html. Give one div the id profile. Inside it, add a paragraph with the attribute data-topic set to hobbies. Write any text in the paragraph.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 4 - Divs, Attributes and a Small Fix
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Custom Data Attributes</title>
</head>
<body>
  <div id="profile">
    <p data-topic="hobbies">My favorite hobbies include competitive programming, reading technical blogs, and photography.</p>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Paragraph text displays normally while the data-topic="hobbies" attribute remains accessible via DOM dataset.
```

---
### Task 3: attendance-fixed.html
**Problem Statement:**
> Find and fix every error in the broken page below, then save it as attendance-fixed.html.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 4 - Divs, Attributes and a Small Fix
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Attendance</title>
</head>
<body>
  <h1>Attendance Report</h1>
  <p>Asha: 92%</p>
  <p>Rohan: 85%</p>
</body>
</html>
```

**Output / Result:**
```text
Corrected unclosed h1 tag, improper nested paragraph tags, and missing language attributes.
```

---

