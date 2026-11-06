# Assignment-07: About Me Page

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Build a short About Me page with semantic tags, an about section and a contact link.

---

## 📝 Tasks & Solutions

### Task 1: about-me.html
**Problem Statement:**
> Create about-me.html with a header (an h1 with your name, and a nav with two links: About to #about and Contact to #contact), an empty main and an empty footer.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 7 - About Me Page
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Me - Structure</title>
</head>
<body>
  <header>
    <h1>Anant Pratap Singh</h1>
    <nav>
      <a href="#about">About</a> |
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main></main>

  <footer></footer>
</body>
</html>
```

**Output / Result:**
```text
Header with name and two navigation anchor links (#about and #contact).
```

---
### Task 2: about-me-section.html
**Problem Statement:**
> Add a section inside main with the id about. Give it an h2 heading About me and one paragraph about yourself.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 7 - About Me Page
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Me - With Section</title>
</head>
<body>
  <header>
    <h1>Anant Pratap Singh</h1>
    <nav>
      <a href="#about">About</a> |
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About me</h2>
      <p>I am a second-year B.Tech Computer Science student at Invertis University, Bareilly. I am passionate about web development, UI/UX design, and open-source contributions.</p>
    </section>
  </main>

  <footer></footer>
</body>
</html>
```

**Output / Result:**
```text
Section with id "about" renders an h2 heading and biographical paragraph.
```

---
### Task 3: about-me-complete.html
**Problem Statement:**
> Add a paragraph inside the footer with a link to your email address (use mailto: in the href). Give the footer the id contact.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 7 - About Me Page
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Me - Complete</title>
</head>
<body>
  <header>
    <h1>Anant Pratap Singh</h1>
    <nav>
      <a href="#about">About</a> |
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About me</h2>
      <p>I am a second-year B.Tech Computer Science student at Invertis University, Bareilly. I am passionate about web development, UI/UX design, and open-source contributions.</p>
    </section>
  </main>

  <footer id="contact">
    <p>Get in touch via email: <a href="mailto:anantpratapsingh@invertis.org">anantpratapsingh@invertis.org</a></p>
  </footer>
</body>
</html>
```

**Output / Result:**
```text
Footer with id "contact" provides a clickable mailto link that opens email client.
```

---

