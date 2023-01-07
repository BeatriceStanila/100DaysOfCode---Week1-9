✅ What is CRUD?

- CRUD refers to the four basic operations a software application should be able to perform – Create, Read, Update, and Delete.

- in such apps, users must be able to create data, have access to the data in the UI by reading the data, update or edit the data, and delete the data.

- in full-fledged applications, CRUD apps consist of 3 parts: an API (or server), a database, and a user interface (UI).

  - the API contains the code and methods
  - the database stores and helps the user retrieve information
  - the user interface helps users interact with the app

<img src="./Screenshots/crud-operations.jpg">

✅ used CRUD and Express to create the backend REST API for a quotes app that shows, adds, modifies and deletes quotes

- an API, or application programming interface, is a set of rules that define how applications or devices can connect to and communicate with each other.

- a REST API is an API that conforms to the design principles of the REST, or representational state transfer architectural style:

  - <b>uniform interface:</b> all API requests for the same resource should look the same, no matter where the request came from

  - <b>client-server decoupling:</b> in REST API design, client and server apps must be completely independent of each other. The only information the client app should know is the URI of the requested resource

        - URI Universal Resource Identifier - a string identifier that refers to a resource on the internet, like a specific document

        - URL Universal Resource Locator - is the location of the resource on the web

  = <b>statelessness:</b> Rest APIs are stateless - each request needs to include all the information necessary for processing it; do not require any server-side sessions

  - <b>cacheability:</b> when possible, resources should be cacheable on the client or server side

    - a cacheable response is an HTTP response that can be cached, that is stored to be retrieved and used later, saving a new request to the server

  - <b>layered system architecture:</b> the calls and responses go through different layers

- REST APIs communicate via HTTP requests to perform standard database functions like creating, reading, updating, and deleting records (also known as CRUD) within a resource.

✅ tested requests to our localhost using Postman

✅ learned how to use Nodemon to continuously update our server without having to close the server and run it again

- nodemon is a tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected.
