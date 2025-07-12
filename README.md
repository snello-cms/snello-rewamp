# snello architecture rewamp
A new modular system.

## snello api
A new architetecture (split in public api and internal api:
- /snapi/*
  - snello protected api (that will create metadata and generate json formly)
- /api/*
  - public unprotected api (that will serve the metadata contents)

## Two micro web app:
- snello-admin => snello-console
  - metadata api 
- snello-contents or => snello-data-admin or snellocms
  - content api management

## snello-admin
We will create a traditional app, with some advanced drag and drop to configure metadata etc.

## snello-contents
Dynamic app with formly json from remote server.
