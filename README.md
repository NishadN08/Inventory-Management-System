# Inventory-Management-System
I have created a inventory management system project for the etg internship
With it one can track his product records and sales happened in his inventory
Also with it one can add new products in the inventory
It has 2 files one for the purchasing purpose and another one for adding products
It stores everything in 2 json files namely-record.json and sales.json
Record.json has all the product details and the sales.json file has all the details of the purchase made

To start with the inventory management program it asks a user to give an input wheather he want to make a purchase or exit
It shows all the products available to purchase in the inventory
Then it asks for the product id which you want to purchase
Once user has entered the id then it asks for how much quantity he wants
Once that is done the program generates a bill on the purchase he made
After that it saves all the details of the purchase in the sales.json file and updates the record.json file according to the purchase made

To start with the Adding products program it asks user to give an input wheather he wants to add or delete a product from our record or exit
It shows all the products available in the inventory
To add the product it will ask for the product id of the product which the user wants to add in record
If the id is already present in the database, it will update the quantity which is to be added
If not it asks for the new product details from the user, according to that it will be added in the database
To delete the product it will ask for the product id of the product which the user wants to delete from  the record
Once the id has entered it will check if the id is present in the database and then will delete the record
After that it will update all the details in the record.json file
