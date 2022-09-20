# Fake RESTful API

A fake RESTful API for testing purposes, running using the npm module **json-server**. You can easily deploy the API to services like Heroku by simply pushing the repository there.

## Installation

Git clone 
https://github.com/krunalbhandekar/json-server-deploy-heroku.git


Now you are ready to deploy to Heroku:

```sh
# Login with your Heroku account
heroku login

# Create the project
heroku create your-api-project-name

# Check status
git status

# Deploy to Heroku
git push heroku master
```

Test your API by running:

```sh
heroku open
```

## Editing the initial data

The database is in the file **[db.json](db.json)**. You can edit the JSON information there.

## After Changes

```sh
git add .
git commit -m "message"
git push heroku master
```

## HTTP Requests & Endpoints

Refer to the [json-server documentation](https://github.com/typicode/json-server) for how to use your API.
