# Assignment-12: Box Model, Cards and Scrolling

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Compare the box sizing types, style a card and make a box scroll.

---

## 📝 Tasks & Solutions

### Task 1: box-model.html
**Problem Statement:**
> Create box-model.html with two boxes (div elements). Both have a width of 200px, padding of 20px and a border of 5px. The first uses box-sizing content-box and the second uses border-box.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 12 - Box Model, Cards and Scrolling
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Box Sizing Comparison</title>
  <style>
    .box {
      width: 200px;
      padding: 20px;
      border: 5px solid #1d3557;
      margin-bottom: 20px;
      background-color: #e9ecef;
    }
    .content-box {
      box-sizing: content-box; /* Total width = 200 + 40 + 10 = 250px */
    }
    .border-box {
      box-sizing: border-box; /* Total width = 200px */
    }
  </style>
</head>
<body>
  <h2>Box Model: content-box vs border-box</h2>
  <div class="box content-box">
    <strong>content-box</strong><br>Total width: 250px
  </div>
  <div class="box border-box">
    <strong>border-box</strong><br>Total width: 200px
  </div>
</body>
</html>
```

**Output / Result:**
```text
Visual comparison showing content-box renders wider than border-box.
```

---
### Task 2: card.html
**Problem Statement:**
> Create card.html with one card: a div with the class card that has a background colour, a 2px border, rounded corners (border-radius 12px) and padding of 16px. Put an h3 heading and a paragraph inside it.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 12 - Box Model, Cards and Scrolling
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>CSS Card Component</title>
  <style>
    .card {
      background-color: #f8f9fa;
      border: 2px solid #ced4da;
      border-radius: 12px;
      padding: 16px;
      max-width: 320px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      font-family: Arial, sans-serif;
    }
    .card h3 {
      margin-top: 0;
      color: #1d3557;
    }
    .card p {
      color: #495057;
      margin-bottom: 0;
    }
  </style>
</head>
<body>
  <div class="card">
    <h3>Computer Science &amp; Engineering</h3>
    <p>Explore core engineering foundations including data structures, web technologies, and systems design.</p>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Renders a rounded card component with 12px corner radius and 16px padding.
```

---
### Task 3: scroll.html
**Problem Statement:**
> Create scroll.html with a div box of fixed height 120px and overflow set to auto. Put five lines of text inside it as paragraphs, Line 1 to Line 5.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 12 - Box Model, Cards and Scrolling
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Scrollable Container</title>
  <style>
    .scroll-box {
      height: 120px;
      overflow: auto;
      border: 2px solid #333;
      padding: 12px;
      width: 250px;
      background-color: #fafafa;
    }
    .scroll-box p {
      margin: 8px 0;
    }
  </style>
</head>
<body>
  <h2>Scrollable Box Demo</h2>
  <div class="scroll-box">
    <p>Line 1: Introduction to Web Design</p>
    <p>Line 2: Semantic HTML Elements</p>
    <p>Line 3: CSS Cascading Rules</p>
    <p>Line 4: Overflow Property Behaviors</p>
    <p>Line 5: End of Log Records</p>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Box of fixed height 120px displays a functional scrollbar when content exceeds height.
```

---

