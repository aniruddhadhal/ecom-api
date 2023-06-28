## E-commerce API using Node.js & MongoDB

This is an E-commerce API made using Node.js & MongoDB.

### Steps to Use the API:

1. Run the following command on the terminal in this project's directory:

2. Start the server using the following command:

3. Open Postman.

4. Make a GET request to `localhost:3000/products`.

5. The products should be visible.

### Steps to Create a New Product:

1. Start the server using the following command:

2. Open Postman.

3. Set the request URL to `localhost:3000/products/create`.

4. Select the "Body" tab below the URL textarea, and then choose "x-www-form-urlencoded".

5. Add `name` and `quantity` as the keys and set the desired values for the keys.

6. Make a POST request.

7. If you receive the message saying "New product added successfully," then you have done everything correctly.

8. The product is created. Check it out by making a GET request to `localhost:3000/products`.

### Steps to Delete a Product:

1. Copy the object ID of the product you want to delete.

2. Add the ID after `localhost:3000/products/`.

3. Make a DELETE request.

4. You will receive a message saying "Deleted successfully."

### Steps to Update the Quantity of a Product:

1. Copy the object ID of the product whose quantity you want to update.

2. Put the ID after `localhost:3000/products/`.

3. After putting the ID, add `/update_quantity/?number={x}` in the URL, where `x` is the number by which you want to increase or decrease the quantity.

Example URL: `localhost:3000/products/{id}/update_quantity/?number={x}`

4. Make a POST request, and you should get a message containing the updated product.

### Tech Stack:

- Node.js
- MongoDB

