# Assignment-13: Flexbox Layouts

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Lay out a navigation bar, centred cards and cards that wrap, using Flexbox.

---

## 📝 Tasks & Solutions

### Task 1: nav-flex.html
**Problem Statement:**
> Create nav-flex.html with a horizontal navigation bar (a nav element) of four links: Home, About, Events and Contact. Use display flex for the bar, give it a dark background and make the link text white.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 13 - Flexbox Layouts
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Flexbox Navigation Bar</title>
  <style>
    nav {
      display: flex;
      background-color: #1d3557;
      padding: 14px 20px;
      gap: 24px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-family: Arial, sans-serif;
      font-weight: bold;
    }
    nav a:hover {
      color: #e63946;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#events">Events</a>
    <a href="#contact">Contact</a>
  </nav>
</body>
</html>
```

**Output / Result:**
```text
Horizontal navigation bar laid out side by side using display: flex.
```

---
### Task 2: centred-cards.html
**Problem Statement:**
> Create centred-cards.html with a div (class row) holding three cards (class card) in one row. Each card has an h3 heading (Starter, Standard, Premium) and a paragraph with the price 199, 349 or 499. Use justify-content and align-items to centre the cards in the row.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 13 - Flexbox Layouts
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Centred Cards with Flexbox</title>
  <style>
    .row {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 20px;
      min-height: 250px;
      background-color: #f1faee;
      padding: 20px;
    }
    .card {
      background-color: white;
      border: 1px solid #a8dadc;
      border-radius: 8px;
      padding: 20px;
      text-align: center;
      width: 140px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      font-family: Arial, sans-serif;
    }
    .card h3 {
      color: #1d3557;
      margin-top: 0;
    }
    .price {
      font-size: 1.25rem;
      font-weight: bold;
      color: #e63946;
    }
  </style>
</head>
<body>
  <div class="row">
    <div class="card">
      <h3>Starter</h3>
      <p class="price">&#8377;199</p>
    </div>
    <div class="card">
      <h3>Standard</h3>
      <p class="price">&#8377;349</p>
    </div>
    <div class="card">
      <h3>Premium</h3>
      <p class="price">&#8377;499</p>
    </div>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Three pricing cards aligned and centered horizontally and vertically in a row.
```

---
### Task 3: wrapping-cards.html
**Problem Statement:**
> Create wrapping-cards.html with the heading Stationery Shop and four cards in a flex-wrap row: Notebook (price 60), Pen (price 15), Bag (price 350) and Book (price 120). Narrow the browser window to check the wrapping.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 13 - Flexbox Layouts
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Wrapping Cards Demo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    .shop-row {
      display: flex;
      flex-wrap: wrap;
      gap: 16px;
    }
    .item-card {
      background-color: #e9ecef;
      border: 2px solid #457b9d;
      border-radius: 8px;
      padding: 16px;
      width: 160px;
      text-align: center;
    }
    .item-card h4 {
      margin: 0 0 8px 0;
      color: #1d3557;
    }
    .item-card p {
      margin: 0;
      font-weight: bold;
      color: #2b2d42;
    }
  </style>
</head>
<body>
  <h1>Stationery Shop</h1>
  <div class="shop-row">
    <div class="item-card">
      <h4>Notebook</h4>
      <p>&#8377;60</p>
    </div>
    <div class="item-card">
      <h4>Pen</h4>
      <p>&#8377;15</p>
    </div>
    <div class="item-card">
      <h4>Bag</h4>
      <p>&#8377;350</p>
    </div>
    <div class="item-card">
      <h4>Book</h4>
      <p>&#8377;120</p>
    </div>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Cards wrap cleanly onto subsequent rows when viewport width is narrowed.
```

---

