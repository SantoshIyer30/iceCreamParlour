# iceCreamParlour
A Simple Python Application for a fictional ice cream parlor cafe that uses SQLite to manage user and owners databases

## 🚀 How to use ?

1. Clone the Repository to your system.
2. ```sh
    git clone https://github.com/SantoshIyer30/iceCreamParlour.git
    cd iceCreamParlor
    ```
3. Open "iceCream.py" and execute the file. This step will create necessary databases for further operations.
4. ```sh
    python iceCream.py
    ```
5. Open "user.py" to access the Parlor like a customer.
6. ```sh
    python user.py
    ```
7. When executed , the application has a text based menu where you get to choose actions from the given options as a user. i.e add and remove items from cart, view offerings, add allergens, suggest new flavours.
8. Open "manage.py" to access the Parlor as a manager.
9. ```sh
    python manage.py
    ```
10. When executed, the manager also has a text based menu which gives the user to choose which action to execute from the given options. i.e view user cart, view inventory, add/ remove items from inventory, view user suggestions , and many more.


## 💻 Test Steps 

### In user.py 
We observe a menu which looks like : 
***Ice Cream Parlor Menu:***
1. ***Add Customer Suggestion***
2. ***Add Allergen***
3. ***Search flavours***
4. ***Add to Cart***
5. ***View Cart***
6. ***Remove from Cart***
7. ***Exit***
***Enter your choice :***

1. Enter the desired choice, For example we press 1 and press enter
2. We are asked to enter our suggested flavour and our name

***Enter your choice: 1***
***Enter suggested flavour name: Blue Berry***
***Enter your name: Santosh***
***Blue Berry  has been suggested.***

3. We can also perform other tasks like adding ice cream to cart, which can be done by pressing 4 and pressing enter
***Enter your choice: 4***
***Enter flavour name to add to cart: Chocolate***
***Chocolate has been added to cart.***

4. We can Confirm the addition by pressing 5 and pressing enter
***Enter your choice: 5***
***Cart contents:***
***(1, 'Chocolate')***

### In 
