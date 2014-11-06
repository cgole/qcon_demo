
Features covered in this app - 

1. Model - CoffeeShops, Reviews, Customers
2. Datasource connectors 
3. Model relations between CoffeeShops, Reviews, Customers so Customers can add Reviews for Coffeeshops.
4. ACls - No write access to Reviews
5. Custom method example in common/models/coffee-shop.js 
6. FE map in client/index.html
7. Strong-studio discovery and migration using mysql and the Coffee model


To run the app, you need to have Mongo running.

Install dependencies - npm i
Run the app - slc run
Open the explorer - http://localhost:3000/explorer
Open the coffeeshop map - http://localhost:3000/index.html
When you run the app for the first time, the database is empty and you dont see any data on the map.
Open coffeeshops.json in the root directory of the app and copy the contents of that file.
Make a post request to /api/CoffeeShops from the explorer. This will add all the coffee shops to the mongo db.
Reload http://localhost:3000/index.html. You should now see the coffeeshops on the map.  


