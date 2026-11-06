# Assignment-09: Tables with Headers and Footers

- **Name:** Anant Pratap Singh
- **Student ID:** BCS2025542
- **Course:** B.Tech CSE - Second Year
- **Subject:** HTML and CSS Introduction Lab (BCS352)
- **Institution:** Invertis University, Bareilly

---

## 🎯 Aim
Build a table with a caption, a header, rows and a footer, and add scope attributes.

---

## 📝 Tasks & Solutions

### Task 1: marks.html
**Problem Statement:**
> Create marks.html with a table that has the caption Marks of Class A. Use thead for the header row (Name, Maths, Science) and tbody for three rows: Asha 78 85, Rohan 64 70 and Neha 91 88.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 9 - Tables with Headers and Footers
  Task: 1
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Student Marks</title>
</head>
<body>
  <table border="1">
    <caption>Marks of Class A</caption>
    <thead>
      <tr>
        <th>Name</th>
        <th>Maths</th>
        <th>Science</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Asha</td>
        <td>78</td>
        <td>85</td>
      </tr>
      <tr>
        <td>Rohan</td>
        <td>64</td>
        <td>70</td>
      </tr>
      <tr>
        <td>Neha</td>
        <td>91</td>
        <td>88</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
```

**Output / Result:**
```text
Table displays caption, header row, and three student records.
```

---
### Task 2: marks-average.html
**Problem Statement:**
> Create marks-average.html with the same caption and header as marks.html, the Asha and Rohan rows (leave out Neha), and a tfoot row called Class average with the average Maths and Science marks of the two students.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 9 - Tables with Headers and Footers
  Task: 2
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Class Average Marks</title>
</head>
<body>
  <table border="1">
    <caption>Marks of Class A</caption>
    <thead>
      <tr>
        <th>Name</th>
        <th>Maths</th>
        <th>Science</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Asha</td>
        <td>78</td>
        <td>85</td>
      </tr>
      <tr>
        <td>Rohan</td>
        <td>64</td>
        <td>70</td>
      </tr>
    </tbody>
    <tfoot>
      <tr>
        <th>Class average</th>
        <td>71</td>
        <td>77.5</td>
      </tr>
    </tfoot>
  </table>
</body>
</html>
```

**Output / Result:**
```text
Includes tfoot displaying Class average: Maths 71, Science 77.5.
```

---
### Task 3: marks-accessible.html
**Problem Statement:**
> Create marks-accessible.html with the same caption, header and Asha and Rohan rows, without the footer row. Add scope="col" to each header cell and scope="row" to each name cell.

**Source Code:**
```html
<!--
  Name: Anant Pratap Singh
  Student ID: BCS2025542
  Institution: Invertis University, Bareilly
  Course: B.Tech CSE - Second Year
  Subject: HTML and CSS Introduction Lab (BCS352)
  Assignment: 9 - Tables with Headers and Footers
  Task: 3
-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Accessible Table</title>
</head>
<body>
  <table border="1">
    <caption>Marks of Class A</caption>
    <thead>
      <tr>
        <th scope="col">Name</th>
        <th scope="col">Maths</th>
        <th scope="col">Science</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">Asha</th>
        <td>78</td>
        <td>85</td>
      </tr>
      <tr>
        <th scope="row">Rohan</th>
        <td>64</td>
        <td>70</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
```

**Output / Result:**
```text
Table structure with semantic accessibility attributes scope="col" and scope="row".
```

---

