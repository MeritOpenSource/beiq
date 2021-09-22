## Mock API server

The mock-api server can be ran with json-server. To install it:

> npm i -g json-server

To run it, execute the following command in the directory of `mock-api.json`

> json-server mock-api.json

The `api.yml` contains a swagger 2 specification for the mock-api server.


## Database

A sqlite database is provided with the following schema

![database schema](/resources/db-schema.png)

The database has also been pre-populated with the following activity

![pre-populated activity](/resources/activity.png)
