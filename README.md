# MVC-with-CRUD
Project Summary

  -The project is to implement the use of CRUD(Create, Read, Update, Delete) Operations using the database SQL queries.
  -The project makes the use of MVC (Model View Controller) architecture.
  -All the requirements are fulfilled as the user can perform the CRUD functionality and navigate around the website.


Design

  -The project contains servlet which shows the content on the page i.e View , services which access the database and       get the data or push the data to database i.e Controller  and models which represent the models and their              respective methods and attributes i.e Model.
  -The functionality implement in the project is based on MVC architecture , so it is very easy to add or remove            components later on if we want to expand the project.
  -I used the bootstrap framework for designing purpose to make website layout attractive.
  -I used the database "employees". In employees database, I performed CRUD operations on the tables "departments" and      titles".
  -When the project runs, there is a homepage and when you click on any button, there is a navigation menu  allows to       navigate to all the areas of the home department and title. You get a link on the Departments and Title and when       you click on that, you get a sub menu showing the CRUD operation names: Add, Delete, New and Update.
  -I have performed the extra credit work which makes use of just JSTL/JSP pages and no servlet. It has the same            navigation menu on the top as the main project has. Also it uses the same tables as the main project.
  -To run the main project just run the jsharma3-mp2 project .
  -To run the extra credit work run the jsharma3-mp2-extra project.
  -Both the projects are done separately.


Development Insights

  -Before working on project ,i was not familiar with IDE , But once I started I found very interesting and  get more       familiar with it .
  -I learned about JSP , JSTL and their interaction with each other using MVC architecture.
  -After working on project I like JSP Servlet and want to learn more about servlet .
  -JSTL tags are easier.

Requirements (Installation, Compile, Run-time, etc)

  -Open the project in Net-beans.
  -Connect the database "employees" with the user "jsharma3" and password "itmd4515".
  -Create a JDBC Connection Pool with name "jsharma3Mp2Pool" using the database connected above.
  -Create a JDBC Resource with name "jsharma3Mp2DS using the connection pool created above. And run the project and you       will see the index page and from there you will be able to navigate through all the pages of the website.
  -The Tools used in the project is "NetBeans IDE version 8.0.2"
  -The Project is  based on MVC architecture. The libraries used are sql,util,annotation,ejb,inject,servlet and           validation.

Expected Results/Known Issues


    More functionality can be added and more tables can be included.
    We can add more security and put some extra validation for users.
    We can use some session implementation to parse some value from one servlet to another java page. It is secure too.
    The date function just takes yyyy-mm-dd right now, which can be made such that it takes other formats.
    The data can be validated on client side using languages like javascript instead of server side so it checks the data before sending it.
    All the data to run the project is provided in the above screenshots.
