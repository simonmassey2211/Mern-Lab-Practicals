1. Experiment Title
CSS Grid Layouts
2. Aim
Create equal-column grids, a responsive gallery, and a named-area dashboard.
3. Software / Tools Required
VS Code or text editor, web browser
4. Theory
CSS Grid is a two-dimensional layout system. grid-template-columns defines columns; fr distributes available space; repeat() repeats track definitions; minmax() sets responsive bounds; grid-template-areas assigns named layout regions.
5. Algorithm / Procedure
52.	Create grid-first.html with six numbered boxes, three equal columns, and 12px gap.
53.	Create gallery.html with six labels and repeat(auto-fill, minmax(150px, 1fr)) plus 10px gap.
54.	Create dashboard-areas.html with 200px and 1fr columns and named header/sidebar/main/footer areas.
6. Program / Queries / Commands
grid-first.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><title>Grid First</title>
<style>
.grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; }
.grid div { background: #dbeafe; padding: 24px; text-align: center; }
</style>
</head>
<body>
<div class="grid"><div>1</div><div>2</div><div>3</div><div>4</div><div>5</div><div>6</div></div>
</body>
</html>

gallery.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><title>Club Photo Gallery</title>
<style>
.gallery { display: grid; grid-template-columns: repeat(auto-fill, minmax(150px, 1fr)); gap: 10px; }
.gallery div { min-height: 120px; display: grid; place-items: center; background: #e5e7eb; }
</style>
</head>
<body>
<h1>Club Photo Gallery</h1>
<div class="gallery">
  <div>Photo 1</div><div>Photo 2</div><div>Photo 3</div>
  <div>Photo 4</div><div>Photo 5</div><div>Photo 6</div>
</div>
</body>
</html>

dashboard-areas.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"><title>Dashboard Areas</title>
<style>
.dashboard { display: grid; grid-template-columns: 200px 1fr; grid-template-areas: "header header" "sidebar main" "footer footer"; gap: 10px; }
header { grid-area: header; background: #1d3557; color: white; padding: 20px; }
aside { grid-area: sidebar; background: #e5e7eb; padding: 20px; }
main { grid-area: main; background: #f3f4f6; padding: 20px; min-height: 180px; }
footer { grid-area: footer; background: #1d3557; color: white; padding: 20px; }
</style>
</head>
<body>
<div class="dashboard">
  <header>Dashboard Header</header>
  <aside>Sidebar</aside>
  <main>Main content</main>
  <footer>Dashboard Footer</footer>
</div>
</body>
</html>

7. Input
Six box numbers, six gallery labels, and dashboard region labels.
8. Output
Six boxes appear in two rows of three; gallery columns adapt to viewport; dashboard areas occupy the requested positions.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'CSS Grid Layouts' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	How is Grid different from Flexbox?
•	What does fr represent?
•	What is grid-template-areas?
