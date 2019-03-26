Outcome required (User Story): The task is to develop a minified version of Stock Management System, with only batches and stocks. 1. The Application should be User based where user login to get access to the application.  
 
2. List batches with the below given fields. Please add CRUD operations to Read/Add/Update/Delete batches (Can create as html forms or Editable tables). Batch table to display BatchId Fruit Variety Quantity 1 Raspberry Amira 12 2 Raspberry Erika 10 3 Raspberry Amira 10 4 Blueberry Alba 15 
 
3. During adding or updating batches, the stocks will be created by grouping the batches based on Fruit and Variety. New stock will be created if the combination Fruit and variety not present already, else increase the quantity of stock. Stock table to display StockId Fruit Variety Quantity 1 Raspberry Amira 22 2 Raspberry Erika 10 3 Blueberry Alba 15 
 
Solution: 
 
The final solution should be written in C# (Framework > 4.5 or .net core) and entity framework to connect to the backend. Expecting best practises from the developer. You can provide the final solution in downloadable format (Use any cloud storage and send us a link to download files) or publish to Azure and provide us the link. Please do not zip solution and try to send it via Email. - Make the front end look presentable - Implement a Design Architecture that suits the application requirements - Database tables should be simple and follow normalization rules. 
- Implement some design patterns /best practises for data access. - Dependency injection using any framework you wish if using .net Framework (>4.5) - Unit testing using any frame work you wish - Logging
