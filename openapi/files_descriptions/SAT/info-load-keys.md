This endpoint is used to keys for SAT consult.
### HTTP Request

POST [https://api.dynamicore.io/internal/sat/sat_key]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| client | Y | Number | Client Identifier | 1 |
| type | Y | String | 	Type of keys for SAT consult. Values: ciec(You need to send the pas parameter), efirma(You need to send the pas, key and cer parameters) | ciec |
| pass | Y | String | Password of keys | |
| key | O | String | Private key. File of type key in Base64 | file.key |
| cer | O | String | Certificate. File of type cer in Base64 | file.cer |