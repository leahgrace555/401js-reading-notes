# Read 06:

## Questions:

1. Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.
- A restaurant rating app could have a location/restaurant, star rating an review. star rating and reviews belong to the restaurant they are written about
2. What is the advantage of an ORM, like Mongoose?
- The advantage of ORM (object relational mapping) is that it allows us to write models, and the program can take care of shifting any necessary changes to the underlying databse connections without you having to change your code.
3. How does the repository pattern compare with an ORM?
-  the repository pattern is like a container that stores data access logic, while the orm is a technoque that allows you to query and manilupate the database/ 
4. When making a repository/facade, what flexibility do you gain?
- A repository pattern is a method of abstracting data that allows for very small changes to the code when changes are made to the underlying database. 
5. Name 3 cloud based NoSQL Databases
- Amazon DynamoDB, Microsoft Azure, MongoDB,  

## vocabulary:

1. **collections:** Collections are a way to store and manipulate groups of objects
2. **the “Repository” design pattern**: A well-documented way of workign with a data source. It performed intermediary tasks between the domain model and the data mapping layers
3. **mongoose middleware:** middleware are functions which are passed control during execution of asynchronous functions. Mongoose has two types: document middleware and query middleware
4. **Object Relation Mapping (ORM):** A method fro converting data between incompatible type systems
