### Commands:

### To run application:
`node server.js`

### To add product:
`Invoke-RestMethod -Method Post -Uri http://localhost:3000/products -ContentType "application/json" -Body '{"name":"Ice cream", "price": 180, "description": "Delicious"}'
`
### To delete product:
`Invoke-RestMethod -Method Delete -Uri http://localhost:3000/products/<product_id>`   - replace product_id with actual id / number. 

### To update product:
`Invoke-RestMethod -Method Put -Uri http://localhost:3000/products/<product_id> -ContentType "application/json" -Body '{"name":"Updated Name", "price": 20, "description": "Updated description"}' - replace product _id with actual id.` 

### List all products:
`Invoke-RestMethod -Uri http://localhost:3000/products`

