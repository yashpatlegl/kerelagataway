
# How to Add the Styled Navbar to Your HTML Page

This guide explains how to use the `navbar.css` file to style your HTML page's navbar.

---

## Steps to Implement the Navbar

### 1. Link `navbar.css` to Your HTML File
Add the following `<link>` tag to the `<head>` section of your HTML file to link the `navbar.css` file:

```html
<link rel="stylesheet" href="navbar.css">
```

---

### 2. Include the Navbar HTML Code
Add the following HTML code inside the `<body>` section of your HTML file:

```html
<header>
  <nav>
    <a class="nav-items active" href="#">Home</a>
    <a class="nav-items" href="#">About</a>
    <a class="nav-items" href="#">Reviews</a>
    <a class="nav-items" href="#">Gallery</a>
    <a class="nav-items" href="#">Contacts</a>
  </nav>
</header>
```

---

### 4. Test Your Page
- Open your HTML file in a browser to ensure the navbar appears styled and functional.

## Notes:
- Make sure `navbar.css` is in the same directory as your HTML file, or update the `href` in the `<link>` tag to the correct relative path.
- Adjust the design and colors in `navbar.css` as needed to suit your requirements.
```

Save this as a markdown file (`README.md`) for step-by-step instructions. Let me know if you'd like further assistance!