* Primekeeper Backend test

Note: You're free to use any framework or library for this exercise.

Points to consider:

* Your commit message matters.
* Your comments matter as well.
* Your folder structure is also taken into consideration.
* This is an open-book test. You may use the Internet.

Scenario: Consider a scenario where a user has a single shopping cart and items that can be put inside the shopping cart. When the user views the shopping cart, he should be able to see the name of the item, the price of the item and the number of such items in the shopping cart. Each user may only have a single shopping cart. Each users will have its first name displayed on the shopping cart.

1. Create a backend codebase in the language of your choice.
2. Create schema migrations for 3 tables - users, shopping_cart and items that fulfills the scenario above. Use a SQL-based database (i.e. MariaDB, MySQL, PostgresSQL or MSSQL)
3. Create a database seeder for each of the 3 tables.
4. Create a config file (.env or similar) that allows the user to modify their database settings.
4. Create an API with the path `/users/shoppingCart` that lists down the items inside the shopping cart for a particular user.
5. Similarly, create an api with the path `/items` that lists down the properties of an item.
6. Lastly, create an api with the path `/users` that gives out the user's name when called.
4. Prepare a README.md with instructions on how to setup the codebase.
5. Send us a link to your code repository to clayton@primekeeper.my and michael@primekeeper.my.
