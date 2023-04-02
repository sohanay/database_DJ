1. What is PostgreSQL? Data can be stored, accessed, and managed using PostgreSQL, a relational database management system.

2. What is the different between SQL and PostgreSQL? PostgreSQL is the database management system, whereas SQL is the language used to query the database.

3. In psql, how do you connect to a database? \c database name

4. What distinguishes the words HAVING and WHERE? 'WHERE' filters rows before grouping using 'GROUP BY', whereas 'HAVING' filters rows after they have been grouped using 'GROUP BY'.

5. What distinguishes an INNER join from an OUTER join? An inner join only brings together tables whose data overlap. An outside join applies the same logic to all data, not only to that which matches the two tables.

6. What is the difference between an LEFT OUTER and RIGHT OUTER join? A left outer retrieves all information from the left table and any information from the right table that intersects it. The data from the right table and any intersecting data from the left table are both returned by a right outer.

7. What is an ORM? What do they do? The services between OOP in a server language and relational data in a database are translated by an object relational mapper, such as SQLAlchemy.

8. What are some differences between making HTTP requests using AJAX and from the server side using a library like requests? AJAX requests, as opposed to server-side requests, are made from Javascript directly in the browser and enable the app to send and receive requests and responses without having to reload the browser page.

9. What is CSRF? What is the purpose of the CSRF token? A website exploitation known as CSRF involves the transmission of unauthorized code from something like concealed data in a form. In order to ensure that the information being returned is coming from the app itself and not some malicious entity, a CSRF token is utilized in a form.

10. What is the purpose of form.hidden_tag()? This is used in a form to place a hidden field such as a CSRF token that is not directly visible to the app user.