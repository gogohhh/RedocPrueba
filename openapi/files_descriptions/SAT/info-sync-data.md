This endpoint is used to sync of the SAT data. Its execute is async to obtain data you should used the endpoint Get Data.
### HTTP Request

POST [https://api.dynamicore.io/internal/sat/sat_key]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| client | Y | Number | Client Identifier | 1 |
| start | Y | String | Start of date to obtain data | 2021-01-01 |
| end | Y | String | End of date to obtain data | 2021-11-31 |