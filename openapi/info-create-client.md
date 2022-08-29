This endpoint retrieves a catalog of client templates.
### HTTP Request

POST [https://api.dynamicore.io/private/clients]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| client_type | Y | String | Type of client | 17 |
| pii[firstname] | Y | String | Firstname of client | Rafael |
| pii[lastname] | Y | String | Lastname of client | Lopez |
| pii[rfc] | Y | String | RFC of client | RALO101086GT4 |
| pii[email] | Y | String | Email of client | email@google.com |