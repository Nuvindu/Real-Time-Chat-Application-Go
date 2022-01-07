# Real-Time-Chat-Application
Chat Application with Instant Messaging feature. Technologies - React, GraphQL, WebSockets

<br/>

### Server

To install Go, follow this [link](https://go.dev/dl/).


Build the structure for the Go GraphQL server using gqlgen library:

```go
go mod init github.com/99designs/gqlgen

go get github.com/99designs/gqlgen

go run github.com/99designs/gqlgen init
```


<br/>

### Client

If yarn package is not yet installed, refer the this [link](https://classic.yarnpkg.com/lang/en/docs/install) to install it.


Create new package: 
```javascript 
yarn init -y 
```

Apollo Client: 
```javascript
yarn add @apollo/client graphql 
```

Chakra UI: 
```javascript
yarn add @chakra-ui/react @emotion/react@^11 @emotion/styled@^11 framer-motion@^5 
 ```

WebSocket: 
```javascript
yarn add subscriptions-transport-ws 
 ```

Shrads React: 
```javascript
yarn add shards-react 
```

<br/>

### Guide

<br/>

Enter to the server folder from a terminal and start the server

 ```javascript
go run server.go
  ```

While the server running, create another terminal and enter to the client folder and start the React app

```javascript
yarn start 
```


<br/>

### References 

<br/>

https://gloutnikov.com/post/2021/graphql-subscriptions-golang-gqlgen-example/

https://www.apollographql.com/docs/react/get-started

https://www.youtube.com/watch?v=E3NHd-PkLrQ

