This endpoint is used to update Contrab.
### HTTP Request

PUT [https://api.dynamicore.io/private/crontab]

### Parameters

| Parameter | Required | Type | Description | Example |
| --------- | --------- | --------- | --------- |--------- |
| company | Y | Number | Id of company | 17 |
| cron | Y | String | Type | */1 * * * * |
| command | Y | String | Comdand | python3 /usr/src/app/start.py >> /usr/src/app/myjob.log 2>&1 |
| user_role | Y | String | Id Role of User | ssdf234 |
| node | Y | Number | Node | 12 |