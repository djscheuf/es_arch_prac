# Mongo DB Ref
Quick list of Mongo DB Console references or related material.

[Manual](https://docs.mongodb.com/manual/mongo/)

## Data Commands

use <<DatabaseName>>
- switches which database you are in.

db
- display which database you are in

db.<<CollectionName>>.insertOne({<<Your Object HERE>>}) ; db.<<CollectionName>>.insertMany([{<<Your Object HERE>>}, ...]) 
- inserts the given document(s) into the provided Collection.

db.<<CollectionName>>.find({<<match criterion>>})
- search for documents matching given criterion within Collection.

db.<<CollectionName>>.find({<<match criterion>>}).pretty()
- above + prettier format.

quit()
- exit cli



