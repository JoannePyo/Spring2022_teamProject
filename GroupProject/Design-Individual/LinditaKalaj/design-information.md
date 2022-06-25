Lindita Kalaj
CS 370 Assignment 5

1. As a user of the system I want to be able to see each store's offering and the amount of product in stock by square feet. 

   -Both customer and employee are allowed to search by store id and product name to pull up the quantity of product in stock at the specified store.

2. The application must allow employees to add new products to the system. As well as delete and edit them.

   -Employees will have special access to the inventory manager with a login and password which will allow them to ass, delete and edit products in the inventory manager

3. The different categories of floors available are tile, stone, wood, laminate and vinyl 

   -in the product class there is a category attribute which will be set to either one of the aforementioned floors.

4. The application must contain a database (DB) of floors. 

   -The database contains the inventory of each store and is connected by the inventory manager which allows users to search, add, delete and edit depending on special permissions.

5. Users must be able to search for products by picking from a hierarchical list, where the first level is the floor category, and the second level is the floor type. 

   -Both customers and employees are able to search for category first and type after. Additionally there are more search functions which the user may use such as color, size, brand, price, and type.

6. Users must also be able to specify an item by typing its name (search functionality). 

   -Both customers and employees are able to search by a name (string)

7. All floors regardless of their category have an associated color, size, brand, type and price

   -In the product class those attributes are included before the type is declared.

8. Categories tile and stone have different materials they are made of, e.g. Tile- porcelain, ceramic, resin; Stone - marble, pebble, slate 

   -In the product type class the material attribute is added to apply to all types of flooring.

9. Wood floors have both a type (solid, engineered, bamboo, etc) and species (oak, hickory, maple, etc.) 

   -The product class includes an attribute isWood which allows the inheriting class to have a type and species when it comes to wood flooring.

10. Laminate can be regular laminate or water resistant, whereas vinyl can be water resistant or waterproof 

    -The product class contains a boolean attribute isWaterproof which allows the inheriting class to use the ipRating to allow a numerical scale to judge the tile on its waterproofing ability

11. The User Interface (UI) must be intuitive and responsive.

    -The ui will be designed by another team for the inventory manager.