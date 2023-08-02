Custom Java HTTP Server, created by Jason Song

The server needs to implement the following systems:

1. Server can listen to a port, port should be configurable so we need a way to read configuration files
2. Open a socket to listen to a port, how many connections and managing the connections. If we want it to be multithreaded to handle multiple connections for example
3. HTTP protocol portion, need to be able to handle read and parse request messages
4. If the client wants to request a file, we need to be able to open and read files from the Filesystem
5. Reply to and write response messages complying with HTTP