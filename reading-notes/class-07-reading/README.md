# Class 07 Reading


#### What code does the server actually run?

The server runs all of the code that handles requests from clients and returns code to them (such as the webpage 
itself which can be rendered client or server side)

#### What Express/HTTP operations map to CRUD operations?

The express functions that map to CRUD operations are .get(), .post(), .put(), and .delete().

#### What does res.send() do?

When you run res.send() it actually sends the response back to the client from the server.

#### What is the order of operations for the three categories of middleware (handler, application, route)?

The order of operations with the three categories of middleware first takes the request runs the application 
middleware, then the router middleware runs, and lastly the handler middleware runs and finally the response
is passed back.

#### What is the parameter next used for?

The next parameter in express is used to move to the next middleware scheduled to run.