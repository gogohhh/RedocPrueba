You must first upload the document here. So that later it generates the document to sign.

This endpoint is used to create a document that will be signed.

To sign the document you must load the widget.
### HTTP Request

POST [https://api.dynamicore.io/marketplace/apps/mifiel/documents]

### Query Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| id | Y | Number | id of client | 424 |
| type | Y | String | type | client |
| field | Y | String | field | acceptance_bc |
| signatories | Y | Array of objects | A list of Signatory Object | [{"email":"","name": "","tax_id": ""}] |
| external_id | O | String | Your unique identifier | Mifiel-0000000000000001 |
| day_to_expire | O | Integer | Number of days the document expires | 1 |
| send_invites | O | boolean | Set True if you want Mifiel to email invitations to attendees. If your participants will sign in the widget embedded within your application send False. | "true" |
| remind_every | O | Integer | Signing reminders will be sent to those who have not signed (if send_mail is enabled) | 0 |
| viewers | O | Array of objects | List of emails from whom they will receive notifications (if enabled) every time someone signs and they will receive a copy of the signed document. | [{"email":"","name": ""}] |