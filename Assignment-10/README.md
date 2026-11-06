# Assignment-10: CSS Fundamentals

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Apply CSS in three ways (inline, internal and linked) and use selectors and text styles.

---

## 📝 Tasks & Solutions

### Task 1: inline-internal.html
**Problem Statement:**
> Create inline-internal.html. In the head, add an internal style block that makes h1 navy and gives the class highlight a yellow background. In the body, add an h1 heading, a paragraph with an inline style that makes its text red, and a paragraph with the class highlight.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 10 - CSS Fundamentals
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Inline and Internal CSS</title>
  <style>
    h1 {
      color: navy;
    }
    .highlight {
      background-color: yellow;
    }
  </style>
</head>
<body>
  <h1>Navy Colored Heading</h1>
  <p style="color: red;">This paragraph is styled with inline CSS to appear red.</p>
  <p class="highlight">This paragraph is styled using an internal class selector with a yellow background.</p>
</body>
</html>
```

**Output / Result:**
```text
A navy heading, red text paragraph, and yellow background highlighted paragraph.
```

---
### Task 2: style.css
**Problem Statement:**
> Create style.css with rules for: all h1 elements (navy), the class note (italic), the id title (underlined), and all p elements (font size 18px and a grey colour).

**Source Code:**
```css
/**
 * Name: Anant Pratap Singh
 * Student ID: BCS2025542
 * Institution: Invertis University, Bareilly
 * Course: B.Tech CSE - Second Year
 * Subject: HTML and CSS Introduction Lab (BCS352)
 * Assignment: 10 - CSS Fundamentals
 * Task: 2
 */

h1 {
  color: navy;
}

.note {
  font-style: italic;
}

#title {
  text-decoration: underline;
}

p {
  font-size: 18px;
  color: grey;
}
```

**Output / Result:**
```text
External stylesheet containing element, class, and ID selectors.
```

---
### Task 3: linked.html
**Problem Statement:**
> Create linked.html that links style.css. It has an h1 with the id title and two paragraphs with the class note. Write any text in them.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 10 - CSS Fundamentals
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Linked External Stylesheet</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1 id="title">Underlined Navy Title</h1>
  <p class="note">First note paragraph rendered in italic, grey, and 18px size.</p>
  <p class="note">Second note paragraph sharing the same styling rules from style.css.</p>
</body>
</html>
```

**Output / Result:**
```text
Applies external styles: underlined navy heading and italic grey paragraphs.
```

---

