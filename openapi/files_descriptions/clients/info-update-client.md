This endpoint is used to update client.
### HTTP Request

PUT [https://api.dynamicore.io/private/clients]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| id | Y | String | ID Clients | 1 |
| pii[firstname] | Y | String | Firstname of client | Rafael |
| pii[lastname] | Y | String | Lastname of client | Lopez |
| pii[rfc] | Y | String | RFC of client | RALO101086GT4 |
| pii[email] | Y | String | Email of client | email@google.com |