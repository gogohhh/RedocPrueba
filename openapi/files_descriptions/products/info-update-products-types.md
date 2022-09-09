This endpoint is used to update products types.
### HTTP Request

PUT [https://api.dynamicore.io/private/products/types]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| id | Y | Number | Id of product type | 17 |
| name | Y | String | Name of product type | Factoraje Ej1 |
| alias | Y | String | Alias of product type | Factoraje |
| company | Y | String | Company of product type| 22 |
| template | Y | Object | Template of product type | [{"field": 36, "score": 1, "validate": {}, "displayname": "Valor Nominal"}, {"field": 37, "score": 2, "validate": {}, "displayname": "Garantia"}, {"field": 39, "score": 3, "validate": {}, "displayname": "Fecha de Creacion"}, {"field": 34, "score": 4, "validate": {}, "displayname": "CLABE"}, {"field": 28, "score": 5, "validate": {}, "displayname": "Contrato Firmado"}, {"field": 40, "score": 6, "validate": {}, "displayname": "Honorarios"}, {"field": 41, "score": 7, "validate": {}, "displayname": "Fecha de Vencimiento"}, {"field": 42, "score": 8, "validate": {}, "displayname": "Fecha de la Factura"}] |
| description | Y | String | Description of product type | Description product type |