1. Experiment Title
Divs, Attributes and a Small Fix
2. Aim
Group content with divs, use id and data attributes, and correct malformed HTML.
3. Software / Tools Required
VS Code or text editor, web browser
4. Theory
The div element is a generic block container. class can be shared by multiple elements, while id should uniquely identify an element. Custom data-* attributes store page-specific metadata. Properly nested and closed tags help browsers interpret the document consistently.
5. Algorithm / Procedure
16.	Create layout.html with header, main, and footer divs using classes.
17.	Create attributes.html with a div id profile and a paragraph data-topic=hobbies.
18.	Correct the missing closing tags in the attendance example.
19.	Open each file in a browser and verify the displayed content.
6. Program / Queries / Commands
layout.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Page Layout</title></head>
<body>
  <div class="header">Page Header</div>
  <div class="main">Main content goes here.</div>
  <div class="footer">Page Footer</div>
</body>
</html>

attributes.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>HTML Attributes</title></head>
<body>
  <div id="profile">
    <p data-topic="hobbies">I enjoy reading, coding, and learning new skills.</p>
  </div>
</body>
</html>

attendance-fixed.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Attendance</title></head>
<body>
  <h1>Attendance Report</h1>
  <p>Asha: 92%</p>
  <p>Rohan: 85%</p>
</body>
</html>

7. Input
The paragraph text and static HTML content are the input.
8. Output
Three layout blocks appear in order; profile paragraph renders; Attendance Report and both attendance lines display correctly.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'Divs, Attributes and a Small Fix' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	What is the difference between class and id?
•	What are data attributes?
•	Why should HTML tags be properly closed?
