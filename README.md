This is a repo with examples usages of [ReasonReact](https://github.com/reasonml/reason-react).
Have something you don't understand? Join us on [Discord](https://discord.gg/reasonml)!

Run this project:

```
npm install
npm run start:server
npm start # in a new tab
```

Once your express server is running with `npm run start:server`,  
open a new tab and start the client with `npm start`
this will run your client written in ReasonML.
Then modify whichever `.re` file in `src/simple/` and the page will reflect the changes automatically.

You can see and modify the graphQL schema, running in express in `apollo-server/schema`. (install nodemon to automatically restart the server)

The client is build using ReasonReact.  
`dataTodoContainer.re` uses graphql from react-apollo to enhance ReasonML components with queries and mutations.
`todoContainer.re` uses the query and mutations
