Bamazon
==============

Description
--------------
Created CLI application that is an Amazon-like storefront with the MySQL. The app will take orders and deplete stock from the store's inventory.

### Packages To Install ###

* inquirer package
* mysql package

### Tools ###
mysql Workbench to create bamazon database where you will build the products table.

![screen shot 2018-02-24 at 11 48 15 pm](https://user-images.githubusercontent.com/675564/36638895-40912d9a-19bd-11e8-9f08-3842c0dbe9a6.png)

### Bamazon Customer Feature ###
Once database is created and files are installed locally, users can run app by typing 'node bamazonCustomer.js' in terminal. The app will first show all products in the database and corresponding details such as item_id, product_name, department_name, price, and stock_quantity. Users are then asked to input an item_id of a widget they want to purchase and the amount of widgets.

![screen shot 2018-02-24 at 11 52 27 pm](https://user-images.githubusercontent.com/675564/36638937-0cc9f388-19be-11e8-860b-dbfe15b8bbf3.png)

![screen shot 2018-02-24 at 11 55 55 pm](https://user-images.githubusercontent.com/675564/36638953-74dd4a56-19be-11e8-84b8-04d295cb5242.png)

The app will either give the user an error message via console log stating the number of widgets wanted is too high if number is above what is in stock_quantity or a console message stating the order has been fulfilled along with the total price.

![screen shot 2018-02-24 at 11 56 44 pm](https://user-images.githubusercontent.com/675564/36638955-7ae700ae-19be-11e8-9c78-12e27629fe43.png)

### Bamazon Manager Feature ###
Users can run app by typing 'node bamazonManager.js' in terminal. The app will first show a list of commands the manager can run by arrowing up or down to select option.

![screen shot 2018-02-28 at 11 28 44 am](https://user-images.githubusercontent.com/675564/36805420-a2bcafc0-1c7a-11e8-955f-51705671530a.png)

User selects "View Products for Sale" and the user will be able to view all items in the database along with the items information such as price and quantity.

![screen shot 2018-02-28 at 11 31 05 am](https://user-images.githubusercontent.com/675564/36805543-eba1228e-1c7a-11e8-8da1-bd836a0d3967.png)

User selects "View Low Inventory" and the user will be able to see any item that has less than 10 items in stock.

![screen shot 2018-02-28 at 11 32 49 am](https://user-images.githubusercontent.com/675564/36805634-262795fa-1c7b-11e8-888c-6652458f4084.png)

User selects "Add to Inventory" and the user will be able to add to the current stock quantity of a specific item.

![screen shot 2018-02-28 at 11 35 06 am](https://user-images.githubusercontent.com/675564/36805764-79cefc2a-1c7b-11e8-9235-eb9cc29949c6.png)

User selects "Add New Product" and the user will be able to make a new item to the database.

![screen shot 2018-02-28 at 11 37 10 am](https://user-images.githubusercontent.com/675564/36805905-c4f3a0ac-1c7b-11e8-940d-26c8a10437bd.png)

User can also select "End Program" and any time in any view to exit out of the application.

![screen shot 2018-02-28 at 11 39 15 am](https://user-images.githubusercontent.com/675564/36806041-1234e150-1c7c-11e8-99e6-0ad76ddf7262.png)

Application also has working validation.

![screen shot 2018-02-28 at 11 42 13 am](https://user-images.githubusercontent.com/675564/36806182-76805482-1c7c-11e8-8455-57633dc041e4.png)
