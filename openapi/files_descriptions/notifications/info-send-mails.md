This endpoint is used to sender emails.
### HTTP Request

POST [https://api.dynamicore.io/sender/email/template]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| name | Y | String | Name  | 22-130102029298373 |
| subject | Y | Object | Subject | {{subject}} |
| html | Y | String | HTML code | <html><body><div><h2>Hola {{name}} </div></h2> <p>Se le ha enviado {{amount}} pesos a la cuenta CLABE: {{account}}. </p></body></html> |
| text | Y | String | Text of Message | Hola {{name}} Se le ha enviado {{amount}} pesos a la cuenta CLABE: {{account}}. |