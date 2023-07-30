# simple-shopping-cart
This project is based on php.
The intention of this shopping cart software is that it should be simple and as minimal as possible.

PHP shopping cart has the following functionality: 
1.Create product gallery for the shopping cart.
2.Manage cart items using the PHP session.
3.Handle add, edit, remove and empty cart actions.
4.Retrieve product information from the database.
I have retrieved information like name, code, price, and photos from the database. The resultant information is in an array format.

I have iterated this resultant array to form the product gallery. Every product in the gallery will have an add-to-cart option.

I have used the PHP shopping cart session to store and manage the items in the cart.

Once the session expires, the cart items get cleared. This code has an option to clear the entire cart or to remove any particular item from the cart.

File Structure:

The shopping cart software example has the following file structure. The below list has the file names and their responsibility.

dbcontroller.php – a generic database layer to help with DAO functions. It also manages the database connection.
index.php – to display the product gallery for the shopping cart.
style.css – to showcase products for the shopping cart. The styles are minimal and cross-browser compatible.
tblproduct.sql – contains SQL script with the product table structure and the data.
product-images – a folder that contains the product images. I have used these images to show the product gallery. 
