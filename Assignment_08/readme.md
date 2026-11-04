1. Experiment Title
Sign-Up Forms and Choices
2. Aim
Create labelled sign-up forms, radio choices, a course dropdown, and required fields.
3. Software / Tools Required
VS Code or text editor, web browser
4. Theory
The form element groups controls. Labels associate accessible text with inputs through for/id. Input types text, email, and password provide suitable controls. Radio buttons sharing a name are mutually exclusive. select and option create dropdowns; required enables browser validation.
5. Algorithm / Procedure
31.	Create signup.html with name, email, and password fields and action thanks.html.
32.	Create choices.html with Female/Male radio buttons and BCA/B.Tech dropdown.
33.	Create signup-required.html with required name/email fields, name placeholder, and submit button.
34.	Test required validation in the browser.
6. Program / Queries / Commands
signup.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Sign Up</title></head>
<body>
  <h1>Sign Up</h1>
  <form method="post" action="thanks.html">
    <label for="fullname">Full name:</label><input type="text" id="fullname" name="fullname"><br>
    <label for="email">Email:</label><input type="email" id="email" name="email"><br>
    <label for="password">Password:</label><input type="password" id="password" name="password"><br>
    <button type="submit">Sign Up</button>
  </form>
</body>
</html>

choices.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Choices</title></head>
<body>
  <h1>Choices</h1>
  <form>
    <fieldset><legend>Gender</legend>
      <label><input type="radio" name="gender" value="female"> Female</label>
      <label><input type="radio" name="gender" value="male"> Male</label>
    </fieldset>
    <label for="course">Course:</label>
    <select id="course" name="course"><option>BCA</option><option>B.Tech</option></select>
  </form>
</body>
</html>

signup-required.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Required Sign Up</title></head>
<body>
  <h1>Sign Up</h1>
  <form>
    <label for="fullname">Full name:</label>
    <input type="text" id="fullname" name="fullname" placeholder="Enter your full name" required><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required><br>
    <button type="submit">Submit</button>
  </form>
</body>
</html>

7. Input
Enter sample name and email; select a gender and course. Do not use real passwords in screenshots.
8. Output
Form fields render with labels; only one radio choice can be selected; dropdown offers two courses; empty required fields trigger browser validation.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'Sign-Up Forms and Choices' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	Why use label for/id?
•	What is the purpose of input type=email?
•	How do radio buttons become a group?
