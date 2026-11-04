1. Experiment Title
CSS Fundamentals
2. Aim
Apply inline, internal, and external CSS using element, class, and ID selectors.
3. Software / Tools Required
VS Code or text editor, web browser
4. Theory
CSS styles HTML elements through selectors and declarations. Inline CSS uses style attributes; internal CSS uses a style element; external CSS uses a linked stylesheet. Element selectors target tags, class selectors target class values, and ID selectors target a unique id.
5. Algorithm / Procedure
38.	Create inline-internal.html with navy h1, yellow highlight class, and red inline paragraph.
39.	Create style.css with h1, .note, #title, and p rules.
40.	Link style.css from linked.html and add the required elements.
41.	Open linked.html to verify the external stylesheet.
6. Program / Queries / Commands
inline-internal.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"><title>CSS Fundamentals</title>
  <style>
    h1 { color: navy; }
    .highlight { background-color: yellow; }
  </style>
</head>
<body>
  <h1>CSS Fundamentals</h1>
  <p style="color: red;">This paragraph uses inline CSS to make its text red.</p>
  <p class="highlight">This paragraph has a yellow background.</p>
</body>
</html>

style.css
h1 { color: navy; }
.note { font-style: italic; }
#title { text-decoration: underline; }
p { font-size: 18px; color: grey; }

linked.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"><title>Linked CSS</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1 id="title">Linked Stylesheet</h1>
  <p class="note">This is the first note paragraph.</p>
  <p class="note">This is the second note paragraph.</p>
</body>
</html>

7. Input
HTML content is the input; CSS rules specify colors, font style, underline, and font size.
8. Output
Heading appears navy, inline paragraph red, highlighted paragraph yellow, and linked page uses external styles.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'CSS Fundamentals' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	What is CSS?
•	How do class and ID selectors differ?
•	What are the three ways to apply CSS?
