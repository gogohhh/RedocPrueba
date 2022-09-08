This endpoint is used to create logs.
### HTTP Request

POST [https://api.dynamicore.io/?action=/diagrams/logs]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| data | Y | String | Data of Log | 1 |
| flow | Y | Number | Id of Flow | 1 |
| node | Y | String | Node to add | 1 |
| uuid | Y | uuid | Id to Log | 670b9562-b30d-52d5-b827-655787665500 |
| extras | Y | Object | Extra config | |