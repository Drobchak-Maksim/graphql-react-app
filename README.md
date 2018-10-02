# graphql-react-app
 You’re importing the required dependencies from the installed packages.
 Here you create the httpLink that will connect your ApolloClient instance with the GraphQL API, 
 your GraphQL server will be running on http://localhost:4000.
 Now you instantiate ApolloClient by passing in the httpLink and a new instance of an InMemoryCache.
 Finally you render the root component of your React app. The App is wrapped with the higher-order 	     	component 
 ApolloProvider that gets passed the client as a prop.
 That’s it, you’re all set to start for loading some data into your app! 😎
