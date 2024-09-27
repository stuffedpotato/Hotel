###### This project is an assignment that I completed for my Object-Oriented Programming in Java class at Langara.

## Hotel, HotelServer, HotelService & HotelClient

- This project is focused on multi-threading and servers.  
- We were provided with the protocol for the server as well as code for the Hotel class.
- I implemented the HotelServer and the HotelService class. The port number for HotelServer is 9999. User needs this port number to be able to connect to the server.
- The HotelServer class uses the HotelService class (which implements Runnable) as its main driver.
- That is, HotelService is the working class for each thread created in HotelServer.

1. Client must first send their name using the 'USER name' protocol. Only then is the client allowed to move forward.
2. Client can choose to reserve the room, cancel their reservation and/or check availability.
3. Client must send 'QUIT' to close the connection.
4. If client uses incorrect protocol, the connection closes automatically.
