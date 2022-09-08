This endpoint is used to update flows.
### HTTP Request

PUT [https://api.dynamicore.io/private/diagrams/flows]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| id | Y | Number | Id of flow | 1 |
| name | Y | String | Name of flow | Flow1 |
| company | Y | Number | Id company of flow | 1 |
| enabled | Y | boolean | Activate Flow | true |
| service | Y | Number | Id of service | 1 |
| diagrams | Y | String | Diagram | CC077 |