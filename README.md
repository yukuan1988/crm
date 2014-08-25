Load sample data into MongoDB by performing the following steps:

* Execute 'mongod' to start the MongoDB daemon
* Navigate to the CustomerManager directory (the one that has initMongoCustData.js in it) then execute 'mongo' to start the MongoDB shell
* Enter the following in the mongo shell to load the seed files:
 * use custmgr
 * load("initMongoCustData.js")
 * load("initMongoSettingsData.js")
 * load("initMongoStateData.js")
