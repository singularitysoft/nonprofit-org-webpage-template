nonprofit-org-webpage-template

<!-- svelte-ignore a11y-missing-attribute -->
<html>
  <head>
    <meta charset="UTF-8">
    <title>Non-Profit Organization</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <header>
      <h1>Non-Profit Organization</h1>
      <nav>
        <ul>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="about">
        <h2>About Us</h2>
        <p>Our non-profit organization is dedicated to providing support and resources to those in need. We believe in creating a better future for all, and we are committed to making a difference in our community through our various programs and initiatives.</p>
      </section>
      <section id="services">
        <h2>Services</h2>
        <ul>
          <li>Food Bank</li>
          <li>Shelter for Homeless</li>
          <li>Education and Job Training</li>
          <li>Health Services</li>
        </ul>
      </section>
      <section id="contact">
        <h2>Contact Us</h2>
        <p>For more information about our organization or to get involved, please contact us:</p>
        <p>
          Non-Profit Organization<br>
          123 Main Street<br>
          Anytown, USA 12345<br>
          Phone: (555) 555-5555<br>
          Email: info@nonprofitorg.com
        </p>
      </section>
    </main>
    <footer>
      <p>Copyright &copy; 2023 Non-Profit Organization</p>
    </footer>
  </body>
</html>

<style>
body {
font-family: Arial, sans-serif;
background-color: #f2f2f2;
}

header {
background-color: #333;
color: #fff;
padding: 20px;
text-align: center;
}

header h1 {
margin: 0;
}

header nav {
display: inline-block;
text-align: right;
}

header nav ul {
list-style: none;
margin: 0;
padding: 0;
display: inline-block;
}

header nav ul li {
display: inline-block;
margin-left: 20px;
}

header nav a {
color: #fff;
text-decoration: none;
}

main {
padding: 20px;
text-align: center;
}

main h2 {
margin-bottom: 20px;
}

section {
background-color: #fff;
box-shadow: 0 2px 4px rgba(0,0,0,0.1);
padding: 20px;
margin-bottom: 20px;
}

footer {
background-color: #333;
color: #fff;
padding: 10px;
text-align: center;
}

form {
text-align: left;
margin: 20px 0;
padding: 20px;
background-color: #fff;
box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

label, input[type="submit"] {
display: block;
margin-bottom: 10px;
}

input[type="text"], input[type="email"], input[type="number"] {
width: 100%;
padding: 10px;
font-size: 16px;
box-sizing: border-box;
}
</style>
