API Endpoints
Cart

POST /cart
Add item to cart.

PUT /cart/update/<userId>
Update cart quantity.

PUT /cart/increase/<id>
Increase cart quantity.

PUT /cart/decrease/<id>
Decrease cart quantity.

GET /cart/<id>
Get cart item details.

Orders

POST /order
Create order.

PUT /orderPayment/<id>
Update payment status.

PUT /orderDelivery/<id>
Update delivery status.

GET /getorderbyuser/<userId>
Get orders by user.
