This endpoint is used to create account.
### HTTP Request

POST [https://api.dynamicore.io/v1/accounts]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| client_id | Y | String | Client Identifier | 1 |
| product | Y | String | Product Identifier | 6 |
| enabled | Y | String | Enabled of product. . Values: Active -> 1, Inactive -> 0 | 1 |
| currency | Y | String | Product currency | 484 |