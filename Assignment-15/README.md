# Assignment-15: Responsive Pages with Media Queries

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Use a media query to change a layout, make a picture scale with its box, and set text sizes with rem units.

---

## 📝 Tasks & Solutions

### Task 1: mobile-first.html
**Problem Statement:**
> Create mobile-first.html with the viewport meta tag in the head, and a div with the class cards holding two cards (class card), each with an h2 heading and a paragraph. Write base styles for phones, then add a media query for screens 600px wide and up that shows the cards side by side.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 15 - Responsive Pages with Media Queries
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mobile First Responsive Cards</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 16px;
    }
    .cards {
      display: flex;
      flex-direction: column; /* Mobile base: Stacked */
      gap: 16px;
    }
    .card {
      background-color: #f8f9fa;
      border: 1px solid #dee2e6;
      border-radius: 8px;
      padding: 16px;
    }
    .card h2 {
      margin-top: 0;
      color: #1d3557;
    }

    /* Screen width 600px and above: Side by side */
    @media (min-width: 600px) {
      .cards {
        flex-direction: row;
      }
      .card {
        flex: 1;
      }
    }
  </style>
</head>
<body>
  <h1>Responsive Cards Layout</h1>
  <div class="cards">
    <div class="card">
      <h2>Web Engineering</h2>
      <p>Fundamentals of client-server architecture, modern DOM standards, and CSS design frameworks.</p>
    </div>
    <div class="card">
      <h2>Mobile Computing</h2>
      <p>Responsive design principles, touch gestures, and progressive web application practices.</p>
    </div>
  </div>
</body>
</html>
```

**Output / Result:**
```text
Cards stack vertically on phone viewports and arrange side by side at >= 600px.
```

---
### Task 2: responsive-image.html
**Problem Statement:**
> Create responsive-image.html with a heading and one picture from the images folder. Set the picture to max-width 100% and height auto, so it shrinks to fit a narrow window.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 15 - Responsive Pages with Media Queries
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive Fluid Image</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
    }
    .image-wrapper {
      max-width: 500px;
      border: 2px dashed #457b9d;
      padding: 10px;
    }
    img.responsive {
      max-width: 100%;
      height: auto;
      display: block;
    }
  </style>
</head>
<body>
  <h1>Fluid Responsive Image</h1>
  <div class="image-wrapper">
    <img src="../images/profile.svg" alt="Responsive profile banner illustration" class="responsive">
  </div>
</body>
</html>
```

**Output / Result:**
```text
Image scales down fluidly on narrow screens without distortion or horizontal overflow.
```

---
### Task 3: responsive-text.html
**Problem Statement:**
> Create responsive-text.html with an h1 heading and a paragraph. Set the body font size to 1rem and the h1 to 1.5rem. Add a media query for screens 600px wide and up that sets the h1 to 2.5rem.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 15 - Responsive Pages with Media Queries
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive Typography</title>
  <style>
    body {
      font-size: 1rem; /* Base 16px */
      font-family: Arial, sans-serif;
      padding: 20px;
      color: #333;
    }

    h1 {
      font-size: 1.5rem; /* Base phone size: 24px */
      color: #1d3557;
      transition: font-size 0.3s ease;
    }

    /* Screen width 600px and up */
    @media (min-width: 600px) {
      h1 {
        font-size: 2.5rem; /* Larger screens: 40px */
      }
    }
  </style>
</head>
<body>
  <h1>Adaptive Heading Size</h1>
  <p>This paragraph maintains a consistent 1rem font size, while the heading scales smoothly from 1.5rem on mobile to 2.5rem on viewports 600px and wider.</p>
</body>
</html>
```

**Output / Result:**
```text
Heading smoothly scales from 1.5rem (mobile) to 2.5rem (viewports >= 600px).
```

---

