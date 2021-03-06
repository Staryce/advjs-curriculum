
# MongoDB

## MongoDB setup + interacting with the shell
  
* [install MongoDB](https://docs.mongodb.com/manual/administration/install-community/)
* run `mongod` to start up the mongo database server
* in another shell, run `mongo` to start up a mongo client (it will connect to the server)

* Go through the following guides (make sure you select "mongo shell" as the client type):
  * [Create](https://docs.mongodb.com/guides/server/insert/)
  * [Retrieve](https://docs.mongodb.com/guides/server/read/)
  * [Retrieve - queries](https://docs.mongodb.com/guides/server/read_queries/)
  * [Retrieve - Operators and Compound Queries](https://docs.mongodb.com/guides/server/read_operators/)
  * [Update](https://docs.mongodb.com/guides/server/update/)
  * [Delete](https://docs.mongodb.com/guides/server/delete/)

Now you have seen enough Mongo to cover all of the basic CRUD operations.

## Interacting with Mongo through Nodejs

Interacting with the shell is often the fastest and easiest way to get something done. It also helps us understand how Mongo works. However, we want to be able to write these CRUD operations as part of a script file or an application.
  
* Follow the [official Node.js quick start guide](https://mongodb.github.io/node-mongodb-native/3.4/quick-start/quick-start/)

## Applying what you have learned

* Make a simple Todo-List app using Express, React, and MongoDB
