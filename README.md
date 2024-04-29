# api

Back-End with REST API

## REST API endpoints

`GET   /apps/all`

Retrieves all apps from the DB and returns the entire array.

`GET   /apps/count`

Retrieves the count of all apps from the DB and returns a number.

`POST  /apps/upsert`

Upserts an app into the DB.

`GET   /playstore/get/${appId}`

Search the play store and return app result with full information.

`GET   /playstore/search/${query}`

Search the play store and return an array of app results with partial information (icon, title).

`GET   /staff/all`

Return all staff members.
