# Burger Mock Database/API

# Setup
Once you have this repo cloned, you will need to install the `json-server` package. This package allows us to serve the json file on our localhost. Once it is served we will be able to make requests for the `database` information.

To install `json-server` open `comand prompt` as an administrator then run this command:
```
  npm install -g json-server
```
<br/>

Now that we have `json-server` installed we can open this project folder in VSCode. Once you have this project open in vscode, open the integrated terminal. Make sure the profile is `command prompt`. Now we will serve our `db.json` file by running this command:
```
  json-server db.json
```

Now we see that our database is served and we can visit `localhost:3000` to see our data.

Keep in mind, when making the http requests in your angular app you need this server to be running for them to work.
