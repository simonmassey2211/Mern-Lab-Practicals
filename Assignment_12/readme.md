1. Experiment Title
Box Model, Cards and Scrolling
2. Aim
Compare box-sizing, style a card, and create a scrollable fixed-height container.
3. Software / Tools Required
VS Code or text editor, web browser
4. Theory
The CSS box model includes content, padding, border, and margin. content-box adds padding and border outside the declared width; border-box includes them within the declared width. overflow:auto enables scrolling when content exceeds the container.
5. Algorithm / Procedure
45.	Create box-model.html with two 200px boxes, 20px padding, and 5px border; apply content-box and border-box.
46.	Create card.html with background, 2px border, 12px radius, and 16px padding.
47.	Create scroll.html with a 120px-high box, overflow:auto, and five paragraphs.
6. Program / Queries / Commands
box-model.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><title>Box Model</title>
<style>
.box { width: 200px; padding: 20px; border: 5px solid navy; margin: 12px; }
.content-box { box-sizing: content-box; background: lightblue; }
.border-box { box-sizing: border-box; background: lightgreen; }
</style>
</head>
<body>
<div class="box content-box">content-box</div>
<div class="box border-box">border-box</div>
</body>
</html>

card.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><title>Card</title>
<style>
.card { background: #eef6ff; border: 2px solid #1d3557; border-radius: 12px; padding: 16px; max-width: 360px; }
</style>
</head>
<body>
<div class="card">
  <h3>Learning HTML &amp; CSS</h3>
  <p>This card demonstrates a background, border, rounded corners, and padding.</p>
</div>
</body>
</html>

scroll.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><title>Scrollable Box</title>
<style>
.scroll-box { height: 120px; overflow: auto; border: 1px solid #333; width: 260px; }
</style>
</head>
<body>
<div class="scroll-box">
  <p>Line 1</p><p>Line 2</p><p>Line 3</p><p>Line 4</p><p>Line 5</p>
</div>
</body>
</html>

7. Input
CSS dimensions and five lines of text.
8. Output
Content-box renders wider than border-box; card shows rounded bordered styling; scroll box allows scrolling through five lines.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'Box Model, Cards and Scrolling' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	What are the four parts of the box model?
•	How does border-box change width calculation?
•	What does overflow:auto do?
