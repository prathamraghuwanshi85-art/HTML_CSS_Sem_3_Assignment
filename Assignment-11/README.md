# Assignment-11: Units and CSS Variables

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Use CSS units and store colours and spacing in variables.

---

## 📝 Tasks & Solutions

### Task 1: units.html
**Problem Statement:**
> Create units.html with a div box 200px wide and 40px high, a div box 50% wide and 40px high, and a paragraph of any text at font size 1.5rem. Give both boxes a background colour.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 11 - Units and CSS Variables
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>CSS Units Demonstration</title>
  <style>
    .fixed-box {
      width: 200px;
      height: 40px;
      background-color: #457b9d;
      margin-bottom: 12px;
      color: white;
      line-height: 40px;
      text-align: center;
    }
    .percent-box {
      width: 50%;
      height: 40px;
      background-color: #2a9d8f;
      margin-bottom: 12px;
      color: white;
      line-height: 40px;
      text-align: center;
    }
    .rem-text {
      font-size: 1.5rem;
      color: #1d3557;
    }
  </style>
</head>
<body>
  <h2>CSS Units (px, %, rem)</h2>
  <div class="fixed-box">200px Fixed Box</div>
  <div class="percent-box">50% Responsive Box</div>
  <p class="rem-text">This paragraph is styled with a 1.5rem font size.</p>
</body>
</html>
```

**Output / Result:**
```text
Renders fixed 200px box, fluid 50% box, and 1.5rem scaled text.
```

---
### Task 2: variables.html
**Problem Statement:**
> Create variables.html with an h1 and a paragraph. In :root, define --main-color as #1d3557, --accent-color as #e63946 and --page-padding as 20px. Use var() for the body colour and padding, and for the h1 colour.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 11 - Units and CSS Variables
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>CSS Variables Demo</title>
  <style>
    :root {
      --main-color: #1d3557;
      --accent-color: #e63946;
      --page-padding: 20px;
    }

    body {
      color: var(--main-color);
      padding: var(--page-padding);
      font-family: Arial, sans-serif;
    }

    h1 {
      color: var(--accent-color);
    }
  </style>
</head>
<body>
  <h1>Accent Colored Heading (#e63946)</h1>
  <p>The body text inherits the main color (#1d3557) and page padding (20px) defined in :root.</p>
</body>
</html>
```

**Output / Result:**
```text
Heading uses accent color #e63946 and paragraph uses main color #1d3557 via var().
```

---
### Task 3: tokens.css
**Problem Statement:**
> Create tokens.css with variables for a primary colour (#1d3557), an accent colour (#e63946), a heading size (2rem) and a spacing value (16px). Use them for the body colour and padding, and for the h1 colour and size.

**Source Code:**
```css
/**
 * Name: Anant Pratap Singh
 * Student ID: BCS2025542
 * Institution: Invertis University, Bareilly
 * Course: B.Tech CSE - Second Year
 * Subject: HTML and CSS Introduction Lab (BCS352)
 * Assignment: 11 - Units and CSS Variables
 * Task: 3
 */

:root {
  --primary-color: #1d3557;
  --accent-color: #e63946;
  --heading-size: 2rem;
  --spacing: 16px;
}

body {
  color: var(--primary-color);
  padding: var(--spacing);
  font-family: Arial, sans-serif;
}

h1 {
  color: var(--accent-color);
  font-size: var(--heading-size);
}
```

**Output / Result:**
```text
Reusable design token stylesheet setting colors, sizes, and padding.
```

---

