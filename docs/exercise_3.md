# Exercise

### Description

In order to search a book using web engine, is needed to design an algorithm in the backend of the web page to find the most suitable book for the user. Basically, the algorithm should take into account user filters (type, category) with logical conditions for each ones. Imagine you have this user interface:

1. Create the algorithm of the backend process when search button is pressed.

2. Which is the most suitable data structure to display the result of the search? Why? Give an example with dummy data.

### Analysis

##### Question 1

There are various alternatives depending on the technologies and frameworks used. Depending on framework, there is no need to even implement an algorithm.

For example, in Spring + Hibernate there are various ways:

- Use Spring repository annotation combined with JPA repository implementation for a simple search
- Use JPA Query annotation, which allows to define a repository method that executes a given Query
- Using Query builders

For this specific task, given it's light complexity, we can retrieve the input from forms and build a query, then map the result to desired objects, but this option requires more code.

There are examples of it in my other repositories, in Java and Pyhon with different frameworks:

- [Example 1](https://github.com/gabriel-stan/formacion-sopra/tree/master/Gabriel_Tienda_Spring/src/main/java/es/rf/tienda/daos)
- [Example 2](https://github.com/gabriel-stan/gestion-tfg)

##### Question 2

Most suitable data structure would be a composed serialized object, which components are application's own models.

Author
- name
- ...

Category
- name

Type
- type

Book
- Author
- Categories[]
- Types[]
- title
- ...

### Task list
### Possible improvements
