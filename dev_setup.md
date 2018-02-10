# Development Environment Setup

The following document is instructions on how to set up MirrorDash. the following software
is required.

* NodeJS
* Yarn
* SQLite3 (for debugging purposes)

Once all are installed, download the two repos for the GraphQL server and ReactJS frontend.

* [COSI-Lab/MirrorDash-Server](https://github.com/COSI-Lab/MirrorDash-Server/)
* [COSI-Lab/MirrorDash-Client](https://github.com/COSI-Lab/MirrorDash-Client/)

Also grab a development copy of the SQLite3 database from Mirror:
[mirrorband.sqlite](https://mirror.clarkson.edu/mirrorband.sqlite). Save this file in the
MirrorDash-Server directory.

Then install the dependencies needed by running `yarn install` in both directories and to start up
the two, run `yarn start` in MirrorDash-Client and `node index.js` in MirrorDash-Server.

The GraphQL server should be running locally on port 4000 and can be tested by going to
http://localhost:4000/graphql/. The React frontend should pop up in a browser window at port 3000.
