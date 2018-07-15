# Shopping List

## Main Features:
- React Frontend
- Express Backend
- Reacstrap Components
- MLab MongoDB Database

## How to run:

Clone this respository.
```
$ git clone https://github.com/JPML94/shopping-list
```

Change directory.
```
$ cd shopping-list
```

Install both server and client modules.
```
$ npm install && npm client-install
```

### Create config file

Create a config folder with a keys.js file and export your MLab Mongo URI.

```
module.exports = {
    mongoURI: '<YOUR_MLAB_DATABASE_URI>'
};
```

Run both client and server with:

```
$ npm run dev
```