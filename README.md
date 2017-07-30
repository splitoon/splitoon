# splitoon

## Frontend
* React/Relay
* Socket.io

## Backend
* gin/graphql-go
* gorilla for websockets
* mysql - sqlx

## Data Model comes later
1) Get a webpage in a messenger chat extension webview
  * Don't even need frontend
  * Gin server set up
  * Oauth/fb tokens set up
2) Setting up a dummy react/relay
3) Figure out what data we store
4) graphql-go
5) see mysql data in the chat extension webview
6) actually make the app

## Backlog
1. Create a gin server to take fb callbacks
   1. Create the fb app and page
   2. Create the gin server and complete the oauth flow
   3. Connect the page to the bot and be able to see that we can send/receive messages
   
