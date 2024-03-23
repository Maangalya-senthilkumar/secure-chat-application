This repository contains two code snippets,that are compatible to run on linux platforms to establish a secure chat applictaion that prevents man in the middle attacks.
To test it on the same machine,initiate two terminals.
Navigate to server.c in terminal 1 and type ./server any port number..port number should not lie between 1-1024 to power on thr server
Navigate to client.c in terminal 2 and type ./client loopback address port number..if two different machines are used,replace loopback address to ip address of server.
When server bids a "bye",session is terminated.
