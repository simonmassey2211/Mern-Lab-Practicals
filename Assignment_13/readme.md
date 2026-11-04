1. Experiment Title
Flexbox Layouts
2. Aim
Use Flexbox for a navigation bar, centered cards, and wrapping product cards.
3. Software / Tools Required
VS Code or text editor, web browser
4. Theory
Flexbox is a one-dimensional layout system. display:flex creates a flex container. justify-content aligns items along the main axis, align-items along the cross axis, gap sets spacing, and flex-wrap allows items to wrap onto multiple lines.
5. Algorithm / Procedure
48.	Create nav-flex.html with four links in a horizontal dark navigation bar.
49.	Create centred-cards.html with Starter, Standard, and Premium cards centered in one row.
50.	Create wrapping-cards.html with four stationery cards and flex-wrap:wrap.
51.	Resize the browser to observe wrapping.
6. Program / Queries / Commands
nav-flex.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><title>Flex Navigation</title>
<style>
nav { display: flex; gap: 24px; background: #222; padding: 16px; }
nav a { color: white; text-decoration: none; }
</style>
</head>
<body>
<nav><a href="#">Home</a><a href="#">About</a><a href="#">Events</a><a href="#">Contact</a></nav>
</body>
</html>

centred-cards.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><title>Centred Cards</title>
<style>
.row { display: flex; justify-content: center; align-items: center; gap: 20px; min-height: 240px; }
.card { padding: 20px; border: 1px solid #777; border-radius: 8px; text-align: center; min-width: 120px; }
</style>
</head>
<body>
<div class="row">
  <div class="card"><h3>Starter</h3><p>199</p></div>
  <div class="card"><h3>Standard</h3><p>349</p></div>
  <div class="card"><h3>Premium</h3><p>499</p></div>
</div>
</body>
</html>

wrapping-cards.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><title>Stationery Shop</title>
<style>
.cards { display: flex; flex-wrap: wrap; gap: 16px; }
.card { flex: 1 1 180px; border: 1px solid #777; padding: 18px; border-radius: 8px; }
</style>
</head>
<body>
<h1>Stationery Shop</h1>
<div class="cards">
  <div class="card"><h3>Notebook</h3><p>Price: 60</p></div>
  <div class="card"><h3>Pen</h3><p>Price: 15</p></div>
  <div class="card"><h3>Bag</h3><p>Price: 350</p></div>
  <div class="card"><h3>Book</h3><p>Price: 120</p></div>
</div>
</body>
</html>

7. Input
Card labels and prices: Starter 199, Standard 349, Premium 499; Notebook 60, Pen 15, Bag 350, Book 120.
8. Output
Navigation links display horizontally; three pricing cards are centered; stationery cards wrap on narrow windows.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'Flexbox Layouts' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	What is a flex container?
•	What does justify-content do?
•	What does flex-wrap do?
