# Login
POST http://api-kenzie-burguer.herokuapp.com/login
{
	"email": "biridin@biridin.com",
	"password": "123456"
}

# Register 
POST https://api-kenzie-burguer.herokuapp.com/register
{
	"email": "biridin@chris.com",
	"password": "123456",
	"name": "biridin"	
}

# Create Product 
POST http://api-kenzie-burguer.herokuapp.com/menu
Authorization: Bearer 
{
	"title": "name",
	"type": "drink",
	"image": "url",
	"price": "6,00",
	"userId": 1
}

# Get Menu 
GET http://api-kenzie-burguer.herokuapp.com/menu

# Add to Cart
POST http://api-kenzie-burguer.herokuapp.com/cart
Authorization: Bearer 
{
	"title": "name",
	"type": "drink",
	"image": "url",
	"price": "6,00",
	"userId": 1
}

# Get Cart
GET http://api-kenzie-burguer.herokuapp.com/cart
Authorization: Bearer 
