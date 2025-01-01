# Node.js Server Freeze: Event Loop Blockage

This repository demonstrates a common issue in Node.js: blocking the event loop with a long-running synchronous operation.  This leads to the server freezing and becoming unresponsive to new requests.

The `bug.js` file contains the problematic code.  The `bugSolution.js` file shows how to resolve this by using asynchronous operations.