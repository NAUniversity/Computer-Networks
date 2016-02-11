# Computer-Networks
Sample codes


Compile  source codes:
$ gcc server.c -o server
$ gcc client.c -o client

Choose any number between 2000 and 65535

Example:
$ server 51547

Then open another terminal on local machine and run
$ client localhost 51547

Send a message, and it will be received on server.

Now, try sending a message to another computer.
Hint: use ip address

