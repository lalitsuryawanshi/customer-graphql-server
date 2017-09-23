# graphql-server
GraphQL server with http CRUD operations

- Included json-server with sample customer data
- Get/Post/Patch/Delete operations are implemented
- Data saved in db.json file locally, can be pointed to any rest data source

How to run (refer package.json file)
- Run json-server on port 3000
  - npm run json:server
  - see data in browser localhost:3000/customers
- Run graphql server on port 4000
  - npm run dev:server
