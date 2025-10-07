Inventory Management Web Application


Why this test?
      This test evaluates your understanding of web applications, which is essential for any new engineer building applications for the web. Flask is chosen as the framework because it is simple, well-written, and easy to learn in a few hours. If you are new to web applications, this test also helps assess your aptitude for learning web application development.

Project Goal
    Create a web application using the Flask framework to manage the inventory of products across different warehouses or locations. The intended use is in a shop or warehouse environment to track various products and their locations.

Functionalities and Database Design
Database Tables
  Product: productid (Primary Key, varchar)

  Location: locationid (Primary Key, varchar)

  ProductMovement: movementid, timestamp, fromlocation, tolocation, productid, qty

Notes:

  Primary keys are text (varchar).

  Either fromlocation or tolocation (or both) can be blank:

  If moving products into a location, fromlocation is blank.

  If moving products out of a location, tolocation is blank.

Views to Implement:
  Add/Edit Product

  Add/Edit Location

  Add/Edit ProductMovement

Report showing product balance quantity in each location

Use Cases
  Create 3-4 products

  Create 3-4 locations

  Make product movements such as:

  Move Product A to Location X

  Move Product B to Location X

  Move Product A from Location X to Location Y

  Repeat to make about 20 such movements

  View product balance in each location in a grid with columns for Product, Warehouse, and Quantity

How to Submit
  When the application is ready, push your code to GitHub.

  Add a README.md file to your repository.

  Include screenshots showing the UI screens and reports.

  Send an email to the requesting engineer or at hraerele.in notifying that your project is done.

Next Steps
  The evaluators will contact you for a walkthrough of your code.

  They may request additional features or changes to evaluate your understanding.

Tips to Ace
  Build a clean, user-friendly UI with well-organized forms and reports.

  Write concise SQL queries if not using an ORM.

  Avoid code duplication by abstracting reusable functions.

Caution
  Do not copy the test from other sources; understand and implement it yourself.

  It is acceptable to ask for help or research online but do the project yourself to build a sustainable programming career
