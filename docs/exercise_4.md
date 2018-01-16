# Exercise

### Description

Propose a technology to develop this computer system. Why?

### Analysis

There are a lot of alternatives to implement a solution for these requirements. Here are a couple examples:

##### Simple Web App
We can use a web framework for our preferred programming language, and implement both front-end and back-end within the framework, using supported plugins and libraries. For example:

- Python + Django framework and his web, templating, ORM and unit testing systems.
- Java + Spring + JPA implementation (like Hibernate) + JUnit
- PHP + CodeIgniter/Symfony

And their pros and cons:

Pros: simple, all-in-one single project
Cons: harder to scale, maintain

##### Micro-services architecture

There is a more complex architecture solution, consisting of separating the application in different modules/services.

For instance, we can separate front-end from backend and implement it as standalone web client app with any JS framework (Angular, React etc.).

Back-end can implement a RESTful service to allow content to be accessible by the web client or a mobile application.

Back-end functionalities can be separated into multiple micro-services, like database service, mail service etc.

Pros: easier maintenance of larger applications, easier scalability and redundancy.

Cons: not suitable for small apps.
