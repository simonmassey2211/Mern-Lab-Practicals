1. Experiment Title
Tables with Headers and Footers
2. Aim
Create marks tables with captions, header/body/footer sections, averages, and scope attributes.
3. Software / Tools Required
VS Code or text editor, web browser
4. Theory
HTML tables organize tabular data using table, caption, thead, tbody, tfoot, tr, th, and td. scope=col and scope=row help assistive technology associate cells with headers. Average is the sum divided by the number of values.
5. Algorithm / Procedure
35.	Create marks.html with caption, header, and three student rows.
36.	Create marks-average.html with Asha and Rohan and calculate each subject average.
37.	Create marks-accessible.html with scope=col on column headers and scope=row on name headers.
6. Program / Queries / Commands
marks.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Marks of Class A</title></head>
<body>
<table border="1">
  <caption>Marks of Class A</caption>
  <thead><tr><th>Name</th><th>Maths</th><th>Science</th></tr></thead>
  <tbody>
    <tr><td>Asha</td><td>78</td><td>85</td></tr>
    <tr><td>Rohan</td><td>64</td><td>70</td></tr>
    <tr><td>Neha</td><td>91</td><td>88</td></tr>
  </tbody>
</table>
</body>
</html>

marks-average.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Marks Average</title></head>
<body>
<table border="1">
  <caption>Marks of Class A</caption>
  <thead><tr><th>Name</th><th>Maths</th><th>Science</th></tr></thead>
  <tbody>
    <tr><td>Asha</td><td>78</td><td>85</td></tr>
    <tr><td>Rohan</td><td>64</td><td>70</td></tr>
  </tbody>
  <tfoot><tr><th>Class average</th><td>71</td><td>77.5</td></tr></tfoot>
</table>
</body>
</html>

marks-accessible.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>Accessible Marks</title></head>
<body>
<table border="1">
  <caption>Marks of Class A</caption>
  <thead><tr><th scope="col">Name</th><th scope="col">Maths</th><th scope="col">Science</th></tr></thead>
  <tbody>
    <tr><th scope="row">Asha</th><td>78</td><td>85</td></tr>
    <tr><th scope="row">Rohan</th><td>64</td><td>70</td></tr>
  </tbody>
</table>
</body>
</html>

7. Input
Marks: Asha 78/85, Rohan 64/70, Neha 91/88. Averages for Asha and Rohan: Maths 71, Science 77.5.
8. Output
Tables show the specified rows; average footer shows 71 and 77.5; accessible table headers carry scope attributes.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'Tables with Headers and Footers' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	What is the purpose of caption?
•	Why use thead and tbody?
•	What do scope=col and scope=row mean?
