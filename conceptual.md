### Conceptual Exercise

Answer the following questions below:

- **What is PostgreSQL?** 
PostgresSQL is a free open source relational database management systeme that supports both JSON (non-relational) and SQL (relational) querying.

- **What is the difference between SQL and PostgreSQL?** PostgreSQL is an object-relational database while SQL is Structured Query Language, a human language for querying. 

- **In `psql`, how do you connect to a database?**
\c DB_NAME
-**What is the difference between `HAVING` and `WHERE`?** `WHERE` specifies some sort of of condition, deciding what row to use. `HAVING` determines which grouped results to keep 

- **What is the difference between an `INNER` and `OUTER` join?** `INNER` join will join only the rows that match the condition in both tables whereas 

- **What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?**  `LEFT OUTER` will join all of the rows from the first table (left), combined with mathcing rows form the second table (right) whereas `RIGHT OUTER` will take the matching rows from the first table (left), combined with the all the rows from the second table (right)

- **What is an ORM? What do they do?** ORM stands for object-relational mapping, instead of writing SQL we map the SQL info into different query objects, we can then call methods on them. An ORM is a translation services between OOP in our server language and relational data in our database. 

- **What are some differences between making HTTP requests using AJAX and from the server side using a library like `requests`?** There are 2 ways to communicate with APIS: client side requests via AJAX, and server side requests. Server side requests use AJAX libraries, don't involve FLASK and can be faster as the speak directly to the API. Server-Side Requests, my prevent browser requests due to Same-Origin Policy, make it easier for server to store and process date, and you need a password to access the API.

- **What is CSRF? What is the purpose of the CSRF token?** CSRF stands for Cross-Site Request Forgery, used to stop a form on any site submitting to another site! It's generated by the server when a form is how, is included in the HTML of the form and is checked by the server on submission 

- What is the purpose of `form.hidden_tag()`? it generates a hidden field, including a tocke that will protect the form against CSRF attaches. 
