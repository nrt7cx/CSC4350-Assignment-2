# CSC4350
1. The project tests three different protocols from client to server. They are IP, PORT and TIMEDELAY. The server and client must also have some command line settings that enable them to set the connection type, port and IP for the client. Once these parameters are set the client can perform four different functions, Run the three protocols listed above or quit the program entirely. The server portion receives one of three protocols and sends the corresponding message back. For example if the -i is set to 127.0.0.1 when the IP protocol on the client is run the server will send 127.0.0.1 back.
2. Use the terminal in your system and cd into the folder location. Use python3 client.py -i xxx.xx.xx.x -p xxxx -t T or U
and use python server.py -p xxxx -t T or U.
3. Can be breached by incoming messages, nothing is implemented if an attacker was to send their own messages. Timedelay can also fail if ran too fast.
