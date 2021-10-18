## Mock API server

Run `npm install` in the directory of this project.

Once the dependencies have downloaded run `npm run mock-api` to start the server.

The `api.yml` contains a swagger 2 specification for the mock-api server. You can paste the contents of `api.yml` in a [swagger editor](https://editor.swagger.io/) to get a human readable version. Below is a preview of the spec.

![api spec](/resources/api-spec.png)


## Database

A sqlite database is provided with the following schema

![database schema](/resources/db-schema.png)

The database has also been pre-populated with the following activity

![pre-populated activity](/resources/activity.png)
