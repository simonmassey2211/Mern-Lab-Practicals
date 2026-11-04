1. Experiment Title
Types of HTML Lists
2. Aim
Create unordered, nested ordered, and description lists.
3. Software / Tools Required
VS Code or text editor, web browser
4. Theory
HTML provides ul for unordered lists, ol for ordered lists, li for list items, and dl with dt/dd for term-description pairs. Lists can be nested to represent subitems.
5. Algorithm / Procedure
24.	Create shopping-list.html with three ul items.
25.	Create canteen-menu.html with two ordered items and a nested ordered list under Sandwich.
26.	Create faq.html with two dt questions and corresponding dd answers.
6. Program / Queries / Commands
shopping-list.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Shopping List</title></head>
<body>
  <h1>Shopping List</h1>
  <ul><li>Notebook</li><li>Pen</li><li>Bag</li></ul>
</body>
</html>

canteen-menu.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Canteen Menu</title></head>
<body>
  <h1>Canteen Menu</h1>
  <ol>
    <li>Samosa</li>
    <li>Sandwich
      <ol><li>Cheese</li><li>Vegetable</li></ol>
    </li>
  </ol>
</body>
</html>

faq.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Library FAQ</title></head>
<body>
  <h1>Library FAQ</h1>
  <dl>
    <dt>How many books can I borrow?</dt><dd>You can borrow up to three books at a time.</dd>
    <dt>Is the library open on Sunday?</dt><dd>No, the library is closed on Sunday.</dd>
  </dl>
</body>
</html>

7. Input
The list items and FAQ answers are static HTML content.
8. Output
The browser displays three bullets, a numbered menu with nested choices, and two question-answer pairs.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'Types of HTML Lists' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	When should ul be used?
•	How do you nest a list?
•	What are dt and dd?
