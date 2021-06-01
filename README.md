# Get started with Apollo Server

### Set up basic Atom server in 9 steps

---

1.  Create a new project: From your preferred development directory, create a directory for a new project and cd into it:


        mkdir graphql-server-example
        cd graphql-server-example

2. Initialize a new Node.js project with npm (or another package manager you prefer, such as Yarn):

        npm init --yes

 *Your project directory now contains a package.json file.*

3. Install dependencies: Applications that run Apollo Server require two top-level dependencies:

  + apollo-server is the core library for Apollo Server itself, which helps you define the shape of your data and how to fetch it.
  + graphql is the library used to build a GraphQL schema and execute queries against it.

Run the following command to install both of these dependencies and save them in your project's node_modules directory:

    npm install apollo-server graphql

create an empty index.js file in your project's root directory

4. Define your GraphQL schema in index.js: Every GraphQL server (including Apollo Server) uses a schema to define the structure of data that clients can query.

5.  Define your data set: After defining  the structure of our data,  define the data itself. Apollo Server can fetch data from any source you connect to (including a database, a REST API, a static object storage service, or even another GraphQL server). 

6. Define a resolver:Data set is defined, but Apollo Server doesn't know that it should use that data set when it's executing a query. To fix this, we create a resolver. 
Resolvers tell Apollo Server how to fetch the data associated with a particular type.

7. Create an instance of ApolloServer: After defining schema, data set, and resolver, provide this information to Apollo Server when we initialize it.

8. Start the server!

9. Execute your first query: Apollo Server hosts GraphQL Playground automatically when you run it in a non-production environment.


---


Refer to : [LINK](https://www.apollographql.com/docs/apollo-server/getting-started/#step-3-define-your-graphql-schema)

