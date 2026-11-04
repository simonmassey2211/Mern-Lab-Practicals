1. Experiment Title
Responsive Pages with Media Queries
2. Aim
Create a mobile-first two-card layout, a responsive image, and responsive heading typography.
3. Software / Tools Required
VS Code or text editor, web browser, image file
4. Theory
Responsive design adapts layouts to viewport sizes. The viewport meta tag sets the layout viewport on mobile. Mobile-first CSS defines base styles for small screens and media queries add changes at larger widths. max-width:100% and height:auto keep images within their containers.
5. Algorithm / Procedure
55.	Create mobile-first.html with viewport metadata and vertically stacked cards.
56.	Add a min-width:600px media query to display cards side by side.
57.	Create responsive-image.html with an image styled max-width:100% and height:auto; provide the image in images/.
58.	Create responsive-text.html with 1rem body, 1.5rem h1, and 2.5rem h1 at 600px and above.
6. Program / Queries / Commands
mobile-first.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mobile First Cards</title>
<style>
.cards { display: flex; flex-direction: column; gap: 16px; }
.card { padding: 20px; border: 1px solid #777; border-radius: 8px; }
@media (min-width: 600px) {
  .cards { flex-direction: row; }
  .card { flex: 1; }
}
</style>
</head>
<body>
<div class="cards">
  <div class="card"><h2>Card One</h2><p>This card stacks on small screens.</p></div>
  <div class="card"><h2>Card Two</h2><p>This card sits beside the first on wider screens.</p></div>
</div>
</body>
</html>

responsive-image.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Responsive Image</title>
<style>img { max-width: 100%; height: auto; }</style>
</head>
<body>
<h1>Responsive Image</h1>
<img src="images/portfolio.jpg" alt="A sample portfolio photograph">
</body>
</html>

responsive-text.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1.0"><title>Responsive Text</title>
<style>
body { font-size: 1rem; }
h1 { font-size: 1.5rem; }
@media (min-width: 600px) { h1 { font-size: 2.5rem; } }
</style>
</head>
<body>
<h1>Responsive Heading</h1>
<p>The heading grows on screens that are at least 600 pixels wide.</p>
</body>
</html>

7. Input
Viewport width and a local image file for the image task.
8. Output
Cards stack on narrow screens and sit side by side at 600px+; image scales to its container; heading grows at the breakpoint.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'Responsive Pages with Media Queries' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	What is mobile-first design?
•	What does a media query test?
•	Why use max-width:100% with height:auto?
