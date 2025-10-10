
---

## One-Week Reading Timetable for _Django 5 for the Impatient_

### Day 1: Foundation and Initial Setup (Chapters 1 & 2)

|Topic|Chapters Covered|Key Concepts|
|:--|:--|:--|
|**Setup & Initial App**|**Chapter 1:** Installing Python and Django, and Introducing the Movies Store Application|Installing Python and Django, creating and running a Django project, introducing the Movies Store application scope, and understanding the Django Model-View-Template (MVT) architecture.|
||**Chapter 2:** Understanding the Project Structure and Creating Our First App|Exploring Django’s project structure (e.g., `manage.py`, `settings.py`), creating your first app ("home"), and using URLs, views, and templates to create pages (Home and About).|

### Day 2: Frontend Structure and Dummy Data (Chapters 3 & 4)

|Topic|Chapters Covered|Key Concepts|
|:--|:--|:--|
|**Aesthetics & Structure**|**Chapter 3:** Designing a Base Template|Using Bootstrap for styling, introducing Django template language (DTL), creating a reusable base template to reduce duplicated code, and managing static files (CSS/images).|
||**Chapter 4:** Creating a Movies App with Dummy Data|Creating a new "movies" app, listing multiple movies, and listing individual movies using dummy data.|

### Day 3: Database Integration (Chapters 5, 6, & 7)

|Topic|Chapters Covered|Key Concepts|
|:--|:--|:--|
|**Models & Queries**|**Chapter 5:** Working with Models|Creating your first Django Model (Movie), installing Pillow for image processing, managing and applying migrations, configuring image upload, and accessing the built-in Django admin interface.|
||**Chapter 6:** Collecting and Displaying Data from the Database|Refactoring the application to remove dummy data and collect/display information directly from the database using model methods like `all()`, `get()`, and `filter()`. Implementing movie search functionality.|
||**Chapter 7:** Understanding the Database|Using a database viewer (SQLite Viewer) to inspect the database structure, customizing the Django admin panel (ordering and searching), and understanding how to switch database engines (e.g., MySQL).|

### Day 4: User Authentication (Chapter 8)

|Topic|Chapters Covered|Key Concepts|
|:--|:--|:--|
|**Auth System**|**Chapter 8:** Implementing User Signup and Login|Creating an "accounts" app, implementing user signup using built-in Django forms (`UserCreationForm`), customizing forms and error displays, implementing user login and handling authentication, and implementing logout functionality.|

### Day 5: CRUD Operations (Chapter 9)

|Topic|Chapters Covered|Key Concepts|
|:--|:--|:--|
|**Data Management**|**Chapter 9:** Letting Users Create, Read, Update, and Delete Movie Reviews|Creating the Review model and applying migrations, implementing complete **CRUD** (Create, Read, Update, Delete) operations for movie reviews, and managing authorizations using `@login_required` decorators to restrict access.|

### Day 6: Shopping Cart Backend (Chapters 10 & 11)

|Topic|Chapters Covered|Key Concepts|
|:--|:--|:--|
|**Session & Commerce**|**Chapter 10:** Implementing a Shopping Cart System|Introducing the concept of web sessions and HTTP protocol limitations, using **Django sessions** to store temporary user-specific data (the cart), adding movies to the cart, listing movies in the cart using custom template filters, and removing movies from the cart.|
||**Chapter 11:** Implementing Order and Item Models|Analyzing store invoices as a blueprint for data modeling, creating the Order model, creating the Item model, and recapping how these models map to the initial Movies Store class diagram.|

### Day 7: Final Functionality and Deployment (Chapters 12 & 13)

| Topic                    | Chapters Covered                                           | Key Concepts                                                                                                                                                                                                                                                              |
| :----------------------- | :--------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Completion & Hosting** | **Chapter 12:** Implementing the Purchase and Orders Pages | Defining the complex `purchase` function to generate Order and Item records from the session cart, creating a purchase confirmation page, implementing an orders page for logged-in users to view past purchases, and recapping the entire Movies Store MVT architecture. |
|                          | **Chapter 13:** Deploying the Application to the Cloud     | Managing Git and creating a GitHub repository, cloning code onto PythonAnywhere, configuring virtual environments, setting up the web application, and configuring static files for production deployment.                                                                |
