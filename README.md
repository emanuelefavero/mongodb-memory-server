# Testing Database

This repo shows how to setup a testing database for Mongoose using [mongodb-memory-server](https://www.npmjs.com/package/mongodb-memory-server).

## Setup

```bash
npm install
```

TIP: _As it is show in the app, it is useful to **separate** the mongoose config file from the app/server file so wew can easily switch between TESTING and PRODUCTION db_

TIP: _A testing database **is stored in memory** and it will be destroyed once the app closes_

### Useful Links

- [The Odin Project on Testing Database](https://www.theodinproject.com/lessons/nodejs-testing-database-operations)

- [mongodb-memory-server GitHub repo](https://github.com/nodkz/mongodb-memory-server)

NOTE: _This app has no further code or dependencies. It is just a demo of how to setup a testing database._
