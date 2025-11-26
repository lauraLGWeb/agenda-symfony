Symfony Contact Manager  – Training Project


 Features to Implement
🔹 1. Base Structure

Create a HomeController.

Create a base layout (base.html.twig) using the Bootstrap starter template.

Add a navbar from Bootstrap.

Define reusable Twig blocks for content.

🔹 2. Homepage

Create home.html.twig extending the base layout.

Set the root URL / to display the homepage.

Display a table of contacts (5 columns: id, name, firstname, phone, action).

Add an “Afficher” button in each row.

🔹 3. Contact Page

Create contact.html.twig using a Bootstrap Jumbotron.

Add a route /contact.

Clicking ACCUEIL returns to /.

Clicking Afficher opens the contact page.

🗄️ Database (Doctrine)
Steps:

Configure database connection in .env.

Create the database agenda.

Create a Contact entity with 7 fields: id, name, firstname, phone, address, city, age.

Run a migration to generate the table.

Insert at least 5 contacts in the database.

Display the contacts dynamically on home.html.twig.

Pass the contact id in the link /contact/{id} and show the correct details.
