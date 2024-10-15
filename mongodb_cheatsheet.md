# MongoDB Cheat Sheet

## Create and Use Database
- Switch to a database (creates if not exists):
``` use database_name ```

## Show All Databases
- List all databases:
``` show dbs ```

## Drop (Delete) a Database
- Drop the current database:
``` db.dropDatabase() ```

## Create a Collection
- Explicitly create a collection:
``` db.createCollection("collectionName") ```

## Drop a Collection
- Drop a specific collection:
``` db.collectionName.drop() ```

## Insert Documents
- Insert a single document into a collection:
``` db.collectionName.insertOne({key: "value"}) ```

- Insert multiple documents into a collection:
``` db.collectionName.insertMany([{key: "value1"}, {key: "value2"}]) ```

## Find Documents with Projection
- Find all documents in a collection, only showing specific fields:
``` db.collectionName.find({}, {field1: 1, field2: 1}) ```

- Find documents matching a condition, only showing specific fields:
``` db.collectionName.find({searchField: "searchValue"}, {field1: 1, field2: 1}) ```
