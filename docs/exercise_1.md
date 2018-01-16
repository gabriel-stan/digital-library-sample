# Exercise 1

### Description

All questions of this test are related with the computer system of a Digital Library. The system is in charge of stock, organize and select all the information of the digital books (there are 3 kinds of extension .epub, .pdf, .txt). Also, the system allows you to search and download books.

Design a basic User Interface of the Web Page to display and manage available books of the digital library.

### Analysis

There are at least two options:

1. Design and implement a static web template (HTML, CSS, JS), for later use within this or any web application.
2. Find a free, ready-to-use template.

For this example, we are going to go with the second option, as it's a lot faster and it provides better graphical results.

After a bit of searching, I've downloaded [this](https://www.phpjabbers.com/free-book-online-store-template-86.php) free template to use with our app. The results will be shown within the app.

### Possible improvements

In any case, if we were to design our own template, we would need a few designs to meet at least the following scenarios:

User/public profile:
- List all books
- Detailed view of a book
- Search by: type, categories, title, author ...

Admin:

All of the above plus:
- Login/Logout
- Add/Edit/Remove/View books
- Add/Edit/Remove/View categories
- Add/Edit/Remove/View types
