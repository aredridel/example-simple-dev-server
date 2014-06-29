# A simple dev server


This is just to demonstrate how to start a server process in [`package.json`](package.json) -- so look at that, particularly the `start` key.

The port is `9080` by default. It's set on the command line -- this isn't general, but the server component I chose (`static-server`) supports it as its second argument.

It runs the server provided by the `static-server` package -- if you wanted to write your own (using express), replace the command-line in the `start` key.
