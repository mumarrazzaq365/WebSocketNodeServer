# Simple WebSocket server using the ws module

This is meant for testing out the capabilities of Unreal Engine's WebSocket client interface locally, but can be sued with non-UE clients too. All the server does is assign unique IDs to client connections, broadcast messages received from a client to all the connected clients, and tell clients how many connected clients there are every 15 seconds. 

To try it out, simply run `npm install`, then `node server`, and have applications connect to ws://localhost:8080. 

#   W e b S o c k e t N o d e S e r v e r  
 