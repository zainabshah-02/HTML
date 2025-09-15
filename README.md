
# 📘 HTML Cheatsheet

A quick reference guide for HTML basics 🚀

---

📌 Basic HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Page Title</title>
</head>
<body>
  <h1>Hello, World!</h1>
</body>
</html>
📌 Headings
html
Copy code
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Smaller Heading</h3>
<h4>Even Smaller</h4>
<h5>Tiny</h5>
<h6>Smallest</h6>
📌 Text Formatting
html
Copy code
<p>This is a paragraph.</p>
<strong>Bold text</strong>
<em>Italic text</em>
<u>Underline</u>
<mark>Highlighted</mark>
<del>Deleted</del>
<ins>Inserted</ins>
<small>Small text</small>
📌 Links & Images
html
Copy code
<a href="https://example.com" target="_blank">Visit Example</a>
<img src="image.jpg" alt="Description" width="200" height="150">
📌 Lists
html
Copy code
<!-- Unordered List -->
<ul>
  <li>Item One</li>
  <li>Item Two</li>
</ul>

<!-- Ordered List -->
<ol>
  <li>First</li>
  <li>Second</li>
</ol>

<!-- Definition List -->
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
</dl>
📌 Tables
html
Copy code
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Zainab</td>
    <td>22</td>
  </tr>
</table>
📌 Forms
html
Copy code
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="username"><br><br>

  <input type="email" placeholder="Email"><br>
  <input type="password" placeholder="Password"><br>
  <input type="checkbox"> Accept Terms<br>
  <input type="radio" name="gender"> Male
  <input type="radio" name="gender"> Female<br>

  <select>
    <option>Option 1</option>
    <option>Option 2</option>
  </select><br><br>

  <textarea rows="3" cols="20">Type here...</textarea><br>
  <button type="submit">Submit</button>
</form>
📌 Multimedia
html
Copy code
<audio controls>
  <source src="song.mp3" type="audio/mpeg">
</audio>

<video controls width="320">
  <source src="video.mp4" type="video/mp4">
</video>

<iframe src="https://example.com" width="400" height="300"></iframe>
📌 Semantic HTML
html
Copy code
<header>Header Content</header>
<nav>Navigation Links</nav>
<main>Main Content</main>
<section>Section Content</section>
<article>Article Content</article>
<aside>Sidebar</aside>
<footer>Footer Info</footer>
📌 Meta & SEO
html
Copy code
<meta name="description" content="Your website description">
<meta name="keywords" content="HTML, CSS, JavaScript">
<meta name="author" content="Your Name">
