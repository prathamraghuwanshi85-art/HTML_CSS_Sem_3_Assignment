# Assignment-06: Types of HTML Lists

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Make a bulleted list, a numbered list with a nested list, and a description list.

---

## 📝 Tasks & Solutions

### Task 1: shopping-list.html
**Problem Statement:**
> Create shopping-list.html with the heading Shopping List and an unordered list of three items: Notebook, Pen and Bag.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 6 - Types of HTML Lists
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Shopping List</title>
</head>
<body>
  <h1>Shopping List</h1>
  <ul>
    <li>Notebook</li>
    <li>Pen</li>
    <li>Bag</li>
  </ul>
</body>
</html>
```

**Output / Result:**
```text
Renders an unordered list with bullet points: Notebook, Pen, Bag.
```

---
### Task 2: canteen-menu.html
**Problem Statement:**
> Create canteen-menu.html with the heading Canteen Menu, a numbered list of two items: Samosa and Sandwich. Under Sandwich, add a nested numbered list of two items: Cheese and Vegetable.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 6 - Types of HTML Lists
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Canteen Menu</title>
</head>
<body>
  <h1>Canteen Menu</h1>
  <ol>
    <li>Samosa</li>
    <li>
      Sandwich
      <ol>
        <li>Cheese</li>
        <li>Vegetable</li>
      </ol>
    </li>
  </ol>
</body>
</html>
```

**Output / Result:**
```text
Renders numbered items 1. Samosa, 2. Sandwich with nested 1. Cheese, 2. Vegetable.
```

---
### Task 3: faq.html
**Problem Statement:**
> Create faq.html with a description list of two questions: How many books can I borrow? and Is the library open on Sunday? Put each question in a dt element and write an answer in a dd element.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 6 - Types of HTML Lists
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Library FAQ</title>
</head>
<body>
  <h1>Frequently Asked Questions</h1>
  <dl>
    <dt>How many books can I borrow?</dt>
    <dd>B.Tech students can borrow up to 4 books for a duration of 14 days.</dd>

    <dt>Is the library open on Sunday?</dt>
    <dd>Yes, the central reading hall is open from 10:00 AM to 4:00 PM on Sundays.</dd>
  </dl>
</body>
</html>
```

**Output / Result:**
```text
Displays questions in dt bold terms followed by indented dd explanations.
```

---

