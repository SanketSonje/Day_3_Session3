# CSS Fundamentals: Selectors, Box Model & Cascade

This project demonstrates CSS fundamentals such as selectors, specificity, inheritance, and the box model using a simple HTML + CSS example.  
It also includes a visual demonstration of the box model via Chrome DevTools before/after screenshots.

# Overview
CSS (Cascading Style Sheets) is used to style and layout web pages — for example, to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations.  

In this project, we focused on:
- Specificity & Inheritance → How element, class, and ID selectors interact.  
- Box Model → How margin, border, padding, and content define the layout.  
- Cascade → How rules are applied based on order and specificity.  

---

# Tasks
- Experiment with specificities and inheritance.  
- Visualize box model via DevTools.  

---

# Deliverables
1. `style.css` – Demonstrates selectors and box model with comments.  
2. **Before/after screenshots** of the DevTools box model (to be added in repo).  

---

# Code Demo

# HTML
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>CSS Specificity & Box Model</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <h1> CSS Specificity & Box Model Demo</h1>

    <section class="content">
      <p>This is a normal paragraph (element selector applies here).</p>
      <p class="text">This paragraph uses a class selector.</p>
      <p id="highlight">This paragraph uses an ID selector (highest specificity).</p>

      <div class="box">
        <h2>Box Model Example</h2>
        <p>This div demonstrates padding, border, and margin.</p>
      </div>

      <div class="box text" id="highlight">
        <h2>Combined Specificity Example</h2>
        <p>This box has class + ID selectors applied.</p>
      </div>
    </section>
  </body>
</html>

```
# Resources

- MDN: CSS First Steps : https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics     
- MDN: Box Model : https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model
