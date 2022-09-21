This endpoint is used to get data of SAT.
### HTTP Request

GET [https://api.dynamicore.io/private/sat/data]

### Query Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| client | Y | Number | Client Identifier | 1 |
| start | O | String | Start of date to obtain data | 2021-01-01 |
| end | O | String | End of date to obtain data | 2021-11-31 |
| limit | O | String | Limit query results | 50 |
| page | O | String | Paginate query results | 1 |