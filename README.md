
# ONLINE LOG READER

The purpose of this document is to provide a detailed architecture design and documentation of the Online Log reader by addressing the background for this project, and the architecturally significant functional requirements.



## Tech Stack

**Client:** React.js, Quil, React-router-dom


**Server:** Node, Express, Socket.io, Node.js, MongoDB



## Deployment

To deploy this project run

Open a new terminal and go to the client folder by writing ```cd client```in the terminal.

Install all the required dependencies for the frontend by writing ```npm install``` in the terminal.

Open a new terminal again and go to the server folder by writing ```cd server``` in the terminal.

Install all the required dependencies for the backend by writing ```npm install``` in the terminal.

Now go back to the client terminal and run ```npm start``` to start the frontend on your local.

Now again go back to the server terminal and run ```npm start``` to start the backend on your local.



## Architecture of the system

![Screenshot (479)](https://user-images.githubusercontent.com/92997379/204464756-ad9c83e2-b4e0-459b-948c-0fdd84a693a4.png)



## Documentation

For the client side, we have used React.js, which is a free and open-source front-end JavaScript library for building user interfaces based on UI components.

To allow Bidirectional and low-latency communication between client and server we have use Socket.io. It uses WebSockets to send and receive data to and from the server. Sockets are really fast and are capable of sending only those data packets which are needed.

Node.js has been used for server-side programming.

MongoDB has been used as a Database to store all the required data changes from the client side. 

