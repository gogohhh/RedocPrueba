This endpoint is used to create role users client.
### HTTP Request

POST [https://api.dynamicore.io/users/add]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| email | Y | String | Email of user | example1@gmail.com |
| role | Y | Object | Role of user | {"Version": 1, "Statement": [{"Action": ["*:*"], "Effect": "Allow", "Resource": "dcore:*:*:*"}]} |