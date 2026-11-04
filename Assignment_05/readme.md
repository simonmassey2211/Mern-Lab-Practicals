1. Experiment Title
Links and Images
2. Aim
Link two HTML pages and display an image with dimensions and alternative text.
3. Software / Tools Required
VS Code or text editor, web browser, image file
4. Theory
The anchor element creates hyperlinks using href. Relative URLs link to files in the same project. The img element embeds an image; alt text provides an accessible description and fallback text. Width and height attributes specify rendered dimensions.
5. Algorithm / Procedure
20.	Create home.html with heading, paragraph, and link to portfolio.html.
21.	Create portfolio.html with a link back to home.html.
22.	Place the instructor-provided image in images/ and update the image path.
23.	Create portfolio-image.html with width and height 200 and descriptive alt text.
6. Program / Queries / Commands
home.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Home</title></head>
<body>
  <h1>Welcome to My Site</h1>
  <p>Visit my <a href="portfolio.html">portfolio</a>.</p>
</body>
</html>

portfolio.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Portfolio</title></head>
<body>
  <h1>My Portfolio</h1>
  <p>Here are some of my projects and interests.</p>
  <a href="home.html">Return to home</a>
</body>
</html>

portfolio-image.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Portfolio Image</title></head>
<body>
  <h1>My Portfolio Image</h1>
  <img src="images/portfolio.jpg" width="200" height="200" alt="A sample portfolio photograph">
</body>
</html>

7. Input
A local image file is required for the image task; replace the placeholder portfolio.jpg with the instructor's image.
8. Output
The links navigate between pages; the image appears at 200 × 200 pixels with meaningful alt text.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'Links and Images' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	What does href specify?
•	Why is alt text important?
•	What is a relative URL?
