# Inventory_management_project
In this project I have made an inventory management system wherein the inventory can be updated by the user and sales file can be generated which tells us about the number of transactions that have taken place.

Overview:-
In this project we have made an inventory management system wherein you can add products to the existing inventory and can update your dataset after selling products.

Description of Files used:-
files.json:- This is our original dataset containing 30 products and their descriptions
inventory.json:- This is the updated version of the 'files.json' file which may have an additional product, a deleted product or an updated product with respect to the 'files.json' file.
files_updated.json:- This is the file which gets updated after every transaction that takes place. For example if someone buys x amount of product with a product ID 19150006 then x number of items is deducted from the original inventory, i.e files.json and saved.
sales.json:- This file indicates the total number of sales that have taken place

Features:-
The user can update, add, delete data in his dataset.
The user can also add GST to his products.
The user also gets to know the time of the transaction.
Once the transactions are done they are saved in another json file called sales so that one can find the total transactions done for a particular time.
The inventory gets updated once the transactions are completed.

Product Features:-
The products have features like product ID, Name ,Weight, Brand name, Quantity available in the dataset,flavour of product.

Transaction Features:-
The transaction features involve Order time, Name of product, amount after GST, quantity, product ID

About:-
Omkar Vijay Gavandi
K.J. Somaiya College of Engineering
