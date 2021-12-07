# Task-01
* Fork the repo
* Clone the forked repo to your local machine
* Resolve the task
* Commit your solution
* Push to GitHub
* Create a pull request

Project structure:
- Readme (read it)
- Data directory contains "products.txt", this file contains products list, each line represent product details sperated by comma.


## Requirements
- Create a class called "Product" that contains the following 
  - attributes (code, name, price, image_name)
  - constructor: accepts default values for attributes.
  - fucntions to get and set all attributes.
- Create a PHP file named "readProducts.php", in this file write a code that do the following:
  - Create an array called "products".
  - Opens "products.txt" file from data directory
  - Read data line by line which means product by product
  - Split each line by comma to get a product details then insert those details into "products" array as Product object.
  - Close the file.
 
- Create a PHP file called 'index.php' 
- Call PHP file "readProducts.php" at the beginning of "index.php" file for using "products" array.
- Now iterate through "products" array that already filled from previous file "readProducts.php" and echo each product into table row, so you will get a table filled with products data.


Done
