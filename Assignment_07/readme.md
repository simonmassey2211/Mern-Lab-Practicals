1. Experiment Title
About Me Page
2. Aim
Build a semantic About Me page with navigation links and an email contact link.
3. Software / Tools Required
VS Code or text editor, web browser
4. Theory
Semantic HTML elements such as header, nav, main, section, and footer describe page structure. Fragment links target element IDs. mailto links open an email application for the specified address.
5. Algorithm / Procedure
27.	Create about-me.html with header, name heading, and About/Contact navigation.
28.	Add a main section with id about, h2, and a short paragraph.
29.	Add a footer with id contact and a mailto email link.
30.	Replace placeholder name and email with personal details.
6. Program / Queries / Commands
about-me.html
<!DOCTYPE html>
<html lang="en">
<head><meta charset="UTF-8"><title>About Me</title></head>
<body>
  <header>
    <h1>[Your Name]</h1>
    <nav><a href="#about">About</a> | <a href="#contact">Contact</a></nav>
  </header>
  <main>
    <section id="about">
      <h2>About me</h2>
      <p>I am a student who enjoys learning technology, solving problems, and building useful projects.</p>
    </section>
  </main>
  <footer id="contact">
    <p>Email: <a href="mailto:you@example.com">you@example.com</a></p>
  </footer>
</body>
</html>

7. Input
Name, biography, and email address are user-provided content.
8. Output
About and Contact links jump to the corresponding sections; email link opens a mail client.
Output screenshot: Insert a browser/terminal screenshot here after running the experiment.
9. Result
The experiment 'About Me Page' was completed successfully. The required concepts and tasks were implemented and verified using the stated tools.
10. Viva-Voce Questions
•	What is semantic HTML?
•	How do fragment links work?
•	What does mailto do?
