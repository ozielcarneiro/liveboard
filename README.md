This program was created to a Parallel and Distributed program class at CESUPA. The objective is to allow two computers to share a paint application remotely. It uses a Client-Server architecture to pass the messages from one client to the other one. The GUI was designed using the Swing library and the communication is done with sockets.

The program assumes that the connection is done through the localhost, so to run the program it is necessary first to run the class Servidor to initialize the server, and then run the class Cliente, initializing the paint application (client). To view the functioning of the program it is necessary to open to client (Cliente class) at least twice. Then any drawing made in one of the blank area in one of the clients, will automatically be drawn in the other clients.

To run the application from different computers connected through a private network, it is necessary to change the first parameter on the new Socket() call, at line 38 of the Conexao.java file, with the new server address.