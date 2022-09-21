This endpoint is used to create order.
### HTTP Request

POST [https://api.dynamicore.io/marketplace/apps/conekta/order/new_order]

### Query Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| account | Y | Integer | Account | 1 |
| operation | O | Integer | operation | 184 |
| customer_info | Y | Object | Object with customer information. Telephone and email is optional | {"name": "Demo", "phone":"", "email":""} |
| items | Y | Object | Object with item information. The price per unit expressed in cents. | { "name": "Box of Cohiba S1s", "unit_price": 1000, "quantity": 1 } |
| payment_method | O | Object | Object with payment method information | { "type": "oxxo_cash" } |
| config | O | Object | config | 0 |