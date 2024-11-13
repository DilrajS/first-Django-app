# Development Notes: Django Polls App

---

## Part 1: Setting Up Django

- **What is the purpose of a database in Django?**  
  In Django, a database is used to store and manage data collected from users or used to display content, such as polls or user accounts.

- **What does the `migrate` command do?**  
  The `migrate` command applies database migrations, setting up tables based on your models.

---

## Part 2: Creating Models

- **What are models in Django?**  
  Models are Python classes that define the structure of your database tables.

- **Why use `ForeignKey` to link `Choice` to `Question`?**  
  Using `ForeignKey` establishes a one-to-many relationship where each `Choice` is related to one `Question`.

---

## Part 3: Using the Admin Site

- **Why customize the Django Admin interface?**  
  Customizing the admin interface improves usability, makes it more user-friendly, and can reflect your app's branding.

---

## Part 4: Writing Views and Templates

- **How does the `get_queryset()` method in generic views work?**  
  The `get_queryset()` method defines the data retrieved from the database and passed to the template.

- **What are templates in Django?**  
  Templates are HTML files with placeholders for dynamic content.

---

## Part 5: Testing

- **Why is it important to write tests for your Django app?**  
  Writing tests ensures your app works as expected and helps prevent future bugs.

- **What does the `TestCase` class do in Django?**  
  The `TestCase` class provides methods for creating a test database and running automated tests.

---

## Part 6: Static Files

- **What are static files in Django?**  
  Static files include assets like CSS, JavaScript, and images that don't change dynamically and are served as-is.

- **Why use `{% load static %}` in templates?**  
  The `{% load static %}` tag is used to reference static files like CSS or images in a template.

---

## Part 7: Customizing the Admin Site

- **How can you customize the Django admin interface?**  
  You can customize the admin interface by modifying the `admin.py` file in your app, registering models, and using classes like `ModelAdmin` to change the display of models.

- **Why is it beneficial to customize the admin interface?**  
  Customizing the admin interface enhances the user experience for administrators, making data management more intuitive and efficient.

---

## Part 8: Adding Third-Party Packages

- **How do you add a third-party package to your Django project?**  
  To add a third-party package, install it using pip (e.g., `pip install package-name`), add it to the `INSTALLED_APPS` in your `settings.py`, and configure it as needed.

- **What is the purpose of the Django Debug Toolbar?**  
  The Django Debug Toolbar provides a set of panels displaying various debug information about the current request/response, aiding in development and debugging.

---
