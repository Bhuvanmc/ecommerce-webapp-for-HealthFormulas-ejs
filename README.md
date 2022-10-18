# ecommerce-webapp-for-HealthFormulas-ejs


1. Problem Statement: 
Healthformulas is online health and Supplement Company. Here a user can register and login into his account. The user details are stored in database. User can view health and supplement products, see the description, details and price. The user can add the products to cart; order products .The invoice must be displayed.

2. Framework Chosen: 
Node.js is a platform for building the i/o applications which are server-side event-driven and made using JavaScript.
To connect node.js and MySQL we used express library.  Express is a small framework that sits on top of Node.js's web server functionality to simplify its APIs and add helpful new features.

3. Methodology adopted:
• Frontend created using express js.
• We have used CSS for styling the web page.
• Backend is created using Nodejs(mysql).
• User can register and login into his account
• The user details are stored in database(mysql). 
• User can view health and supplement products, see the description, details and price in products web page

4. UI and Database Design

1)Login or Home page:
![image](https://user-images.githubusercontent.com/59958031/196373189-12e54483-0abb-4fd8-9b7a-80e956cb07d1.png)

2)Registration  Page: 
![image](https://user-images.githubusercontent.com/59958031/196373299-121d2704-81f5-4e8d-a700-0a27c8b30ef7.png)


3)Products page:
![image](https://user-images.githubusercontent.com/59958031/196373735-f58796e6-a2c2-435b-94e4-e013b67fec22.png)
![image](https://user-images.githubusercontent.com/59958031/196373899-db70ad81-6537-49d8-8dfd-b75362b759a0.png)

4)Cart page:
![image](https://user-images.githubusercontent.com/59958031/196374175-9c0e4b6f-9c63-43b5-b4b6-9a38c0f4c98c.png)

5)Checkout page
![image](https://user-images.githubusercontent.com/59958031/196375134-7f49f9ad-18b8-4bf0-bdef-c9ce6e0ff22f.png)


6)Invoice:
![image](https://user-images.githubusercontent.com/59958031/196376059-3c53c79a-5b94-44ec-808a-d0f1423f9e73.png) 

Database Design: 

Database name: Healthformulas


There are 3 tables:


• User table to store user details like Name, Email, Address, City, State, Country.

• Products table to store details like product id, product name, price, link to the product picture.

• Categories table to store the category id, and category name under which the products lie.
