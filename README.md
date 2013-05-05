# purge

A stupid simple tool to clear out a CouchDB database.


## Dependencies

[node.js](http://nodejs.org/)


## Install
    $ git clone https://github.com/snbartell/couch-purge.git
    $ npm i -g


## Features

- Delete and recreate couchdb database.
- Ensure survival of security and design documents.
- Safe mode saves designs and security to disk before wiping out database.


## Usage


## Example

### single db
    $ couch-purge localhost:5984 test

### several dbs
    $ couch-purge localhost:5984 test1,test2,test3
    
### single db, safely
    $ couch-purge --safe localhost:5984 test
    

# License

MIT
