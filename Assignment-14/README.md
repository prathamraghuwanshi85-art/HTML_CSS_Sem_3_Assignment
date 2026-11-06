# Assignment-14: CSS Grid Layouts

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Make a grid with equal columns, a responsive gallery and a layout with named areas.

---

## 📝 Tasks & Solutions

### Task 1: grid-first.html
**Problem Statement:**
> Create grid-first.html with six boxes (div elements) showing the numbers 1 to 6, in a grid of three equal columns (fr units) with a gap of 12px.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 14 - CSS Grid Layouts
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Equal Columns CSS Grid</title>
  <style>
    .grid-container {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      gap: 12px;
      max-width: 600px;
    }
    .grid-box {
      background-color: #457b9d;
      color: white;
      padding: 30px;
      text-align: center;
      font-size: 1.5rem;
      font-weight: bold;
      border-radius: 6px;
    }
  </style>
</head>
<body>
  <h2>3-Column Equal Grid (fr units)</h2>
  <div class="grid-container">
    <div class="grid-box">1</div>
    <div class="grid-box">2</div>
    <div class="grid-box">3</div>
    <div class="grid-box">4</div>
    <div class="grid-box">5</div>
    <div class="grid-box">6</div>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Six numbered boxes arranged in two rows of three equal columns.
```

---
### Task 2: gallery.html
**Problem Statement:**
> Create gallery.html with an h1 heading Club Photo Gallery and six boxes labelled Photo 1 to Photo 6. Use grid-template-columns with repeat(auto-fill, minmax(150px, 1fr)) and a gap of 10px.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 14 - CSS Grid Layouts
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Responsive Photo Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
      gap: 10px;
    }
    .photo-box {
      background-color: #2a9d8f;
      color: white;
      padding: 40px 10px;
      text-align: center;
      font-weight: bold;
      border-radius: 4px;
    }
  </style>
</head>
<body>
  <h1>Club Photo Gallery</h1>
  <div class="gallery-grid">
    <div class="photo-box">Photo 1</div>
    <div class="photo-box">Photo 2</div>
    <div class="photo-box">Photo 3</div>
    <div class="photo-box">Photo 4</div>
    <div class="photo-box">Photo 5</div>
    <div class="photo-box">Photo 6</div>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Responsive auto-fill grid that adjusts number of photo columns per row dynamically.
```

---
### Task 3: dashboard-areas.html
**Problem Statement:**
> Create dashboard-areas.html with a grid of two columns, 200px and 1fr. Use grid-template-areas to place a header and a footer across both columns, a sidebar on the left and a main area on the right.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 14 - CSS Grid Layouts
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dashboard Grid Areas</title>
  <style>
    .dashboard {
      display: grid;
      grid-template-columns: 200px 1fr;
      grid-template-areas:
        "header header"
        "sidebar main"
        "footer footer";
      gap: 10px;
      min-height: 400px;
      font-family: Arial, sans-serif;
    }
    .header {
      grid-area: header;
      background-color: #1d3557;
      color: white;
      padding: 16px;
    }
    .sidebar {
      grid-area: sidebar;
      background-color: #f1faee;
      border: 1px solid #a8dadc;
      padding: 16px;
    }
    .main {
      grid-area: main;
      background-color: #e9ecef;
      padding: 16px;
    }
    .footer {
      grid-area: footer;
      background-color: #1d3557;
      color: white;
      padding: 12px;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="dashboard">
    <div class="header">Dashboard Header (Spans Both Columns)</div>
    <div class="sidebar">Sidebar (200px width)</div>
    <div class="main">Main Analytics &amp; Reports Content (1fr fluid)</div>
    <div class="footer">Dashboard Footer (Spans Both Columns)</div>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Full dashboard template with header across top, sidebar on left, main on right, and footer across bottom.
```

---

