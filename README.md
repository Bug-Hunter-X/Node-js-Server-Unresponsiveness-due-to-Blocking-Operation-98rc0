# Node.js Server Unresponsiveness
This repository demonstrates a common issue in Node.js applications: server unresponsiveness caused by blocking operations within the request handler.  The `server.js` file contains a simple HTTP server with a long-running synchronous operation that blocks the event loop.  This prevents the server from responding to subsequent requests.

The `serverSolution.js` file demonstrates a solution using asynchronous operations to prevent the event loop from being blocked. 