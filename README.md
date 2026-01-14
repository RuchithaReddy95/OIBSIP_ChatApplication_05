OIBSIP_ChatApplication_05

Description:
A Python-based client-server chat application that enables multiple users to communicate in real time. The project uses socket programming, threading, and a Tkinter-based GUI for the client interface.

--------------------------------------------------------------
TABLE OF CONTENTS

- Installation
- How to Use
- Features
- Description of Files
- Tech Used
- Methodology

--------------------------------------------------------------
INSTALLATION

1. Download this repository as a ZIP file or clone it.
2. Extract the folder.
3. Ensure both server.py and client.py are present.
4. Run the server file first:

   python server.py

5. Open a new terminal and run the client file:

   python client.py

Note: Run multiple client instances to test multi-user chat.

--------------------------------------------------------------
HOW TO USE

1. Start the server.
2. Run the client application.
3. Enter a username when prompted.
4. Type messages in the input box and click Send.
5. Messages are broadcast to all connected users.
6. Close the client window to leave the chat.

--------------------------------------------------------------
FEATURES

- Real-time chat using TCP sockets
- Multiple client support
- Username-based messaging
- GUI-based client using Tkinter
- Auto-scrolling chat window
- Server-side broadcasting of messages
- Handles client join and disconnect notifications

--------------------------------------------------------------
DESCRIPTION OF FILES

File Name        | Description
-----------------|----------------------------------------------
server.py        | Manages client connections and message broadcasting
client.py        | GUI-based chat client for sending and receiving messages

--------------------------------------------------------------
TECH USED

- Language: Python
- Libraries: Tkinter, Socket, Threading

--------------------------------------------------------------

METHODOLOGY

Chat Application Workflow:

1. Server starts and listens for incoming client connections.
2. Client connects to the server and sends a username.
3. Server maintains a list of connected clients.
4. Messages sent by one client are broadcast to all clients.
5. Threading allows simultaneous communication.
6. GUI displays messages in real time.
7. Server handles client disconnects gracefully.

--------------------------------------------------------------
Author: @Ruchitha

THANK YOU!
