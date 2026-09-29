
<div align="center">

# 🎨 Responsive Web Design
### HTML & CSS Practice Project

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">
</p>

<p>
  <b>A beginner-friendly project to explore HTML, CSS, Flexbox, and responsive design.</b>
</p>

[Overview](#-overview) •
[Features](#-features) •
[Installation](#-installation) •
[Code](#-code) •
[Future Improvements](#-future-improvements)

</div>

---

## 📌 Overview

This project demonstrates the fundamentals of HTML and CSS.
It contains a simple webpage displaying a "Hello" message with
CSS styling and a responsive media query.

The project is intended for beginners learning web development.

## ✨ Features

- 🧱 Basic HTML5 structure
- 🎨 CSS styling and colors
- 📱 Responsive media queries
- 🧭 Flexbox navigation example
- 🖼️ Background image example
- 💻 Simple and beginner-friendly code

## 🖥️ Preview

<div align="center">

### Default View

<img src="https://placehold.co/600x180/000000/ff3333?text=Hello" alt="Hello preview">

*Black background with red text.*

### Responsive View

<img src="https://placehold.co/180x180/008000/ffffff?text=Hello" alt="Responsive Hello preview">

*Green background when the viewport width is between 100px and 200px.*

</div>

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Webpage structure |
| CSS3 | Styling and layout |
| Media Queries | Responsive design |
| Flexbox | Navigation layout experiment |

## 📂 Project Structure

```text
Responsive-Web-Design/
│
├── index.html
├── style.css
└── README.md
```

## 🚀 Installation

**Step 1:** Clone the repository.

```bash
git clone https://github.com/your-username/your-repository.git
```

**Step 2:** Open the project folder.

```bash
cd your-repository
```

**Step 3:** Open `index.html` in your browser.

You can also use the Live Server extension in VS Code.

## 💻 Code

<details>
<summary><b>📄 HTML (index.html)</b></summary>

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
  <title>Responsive Web Design</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div>Hello</div>
</body>
</html>
```

</details>

<details>
<summary><b>🎨 CSS (style.css)</b></summary>

```css
div {
  color: red;
  background-color: black;
}

@media (min-width: 100px) and (max-width: 200px) {
  div {
    background-color: green;
  }
}
```

</details>

## 📱 Responsive Design

The project uses a CSS media query to change the background color
based on the viewport width.

| Screen width | Background |
|---|---|
| 100px–200px | 🟢 Green |
| Below 100px | ⚫ Black |
| Above 200px | ⚫ Black |

## 🎯 Learning Objectives

- Understand HTML document structure.
- Apply CSS properties to HTML elements.
- Learn how media queries work.
- Understand basic responsive design.
- Explore Flexbox for page layouts.

## 🌟 Future Improvements

- [ ] Add a responsive navigation bar.
- [ ] Create a modern homepage.
- [ ] Add CSS animations and transitions.
- [ ] Improve mobile and desktop layouts.
- [ ] Add interactive JavaScript features.

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## 📄 License

This project currently has no specified license.

---

<div align="center">

### ⭐ If you find this project useful, give it a star!

**Made with ❤️ while learning HTML & CSS**

</div>
