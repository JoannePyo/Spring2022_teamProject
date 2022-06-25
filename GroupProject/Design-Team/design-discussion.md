# Team 3 Group Design

## Individual Design


### Design 1:
![image](https://user-images.githubusercontent.com/66324119/160754458-5dcb4c2b-434a-44c5-ad68-7fdfdae6c52b.png)
#### Pros:
- Employee and user are there they have attributes and functions that are suitable for our design. 
- Joannes design involves a database. 
- Search floor is also a pro because it allows users and employees to access it to search floor by name.
- She separated the floor types into individual classes.
#### Cons:
- The floor classes contain only functions instead of attributes and we decided as a team to have attributes with floor types. 
- Joanne is also missing the multipliers with makes the design a little less clear. 
- Theres no store class which would allow users and employees to search by store.


### Design 2:
![image](https://user-images.githubusercontent.com/66324119/160754878-7ecb3b55-f310-4c37-9421-8c58e63ace74.png)
#### Pros:
- Her design has an inventory manager that alters the inventory for the user and employee. 
- This design also has a database for the program to link to. 
- This design also has a customer and employee class that we are looking to implement in out team design
#### Cons:
- Floor types aren’t separated and can be confusing to the team that’s building the app.
- There are no store classes which can make the design harder to understand. 
- The relations are not clear enough in her design


### Design 3:
![image](https://user-images.githubusercontent.com/66324119/160754902-9864ddb7-0092-4952-918b-5aa07db6e30a.png)
#### Pros:
- He only has the inventory manager linked to the employee which does not allow customers access to the inventory manager. 
- Xifang also has floor type split up into individual classes which makes it easier to build from the design.
#### Cons:
- He doesn’t have a store id which differentiate stores and cant allow the user to search individual stores.
- Employee doesn’t have a search function and they should be able to look up inventory


### Design 4:
![image](https://user-images.githubusercontent.com/66324119/160754950-9a015e69-1523-48ad-90cf-700cc88be74e.png)
#### Pros:
- Aisha has a search function for quantity.
- Has a store class and a storied for the user to search through.
- Employee and User separately which is what were looking for in the design.
- Arrows are also descriptive so the reader can understand the relationship.
#### Cons:
- She has the types within one class and that can make it difficult for the team to decipher the information. 
- Even though she has a search function she doesn’t have a quantity attribute.


### Design 5:
![image](https://user-images.githubusercontent.com/66324119/160755281-926f1fc9-17c0-4fa2-9964-a3b37ab5b6ee.png)
#### Pros:
- Her uml is simple to read and her arrows/relationships are descriptive. 
#### Cons:
- Her employee and user classes are together and we as a group think its better to separate. 
- She also doesn’t have a store to be able to search through. 
- Her floor types aren’t descriptive.


## Team Design:
![image](https://user-images.githubusercontent.com/66324119/160757955-3c8afbd9-347a-4f12-b265-9ef5b945acba.png)

We agreed as a team to have separate employee and customer classes because they have different permissions and access to different objects. We also agreed to separate the floor type for readability. There is a separate store class implemented to allow customers and employees to search materials in different stores. The inventory manager was also included to allow the employee to add and remove products, this also disallows customers to add and remove products. We also added a search manager to help customers and employees search without directly linking them to the store.


## Summary:
We learned that even though we have different opinions we are still able to compromise and make everyone happy. We also learned that readability is important for everyone because perspectives are different. When a design is simple its easier for everyone to understand and be on the same page. We learned that there needs to be a store class where we can search each individual stores. There was also a better way to do a search function as an interface which we learned from Joanne. Some team members were unclear about the relationship and arrows in regards to the UML design as a team we did some research and got everyone up to speed.
