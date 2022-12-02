
* **Course** : Computer Networks | University 5th semester project


## How to run client and server file:
* First compile the server.c file and run using this format : ./server portnumber(any range except 0-1023)
* Then compile the client.c file and run using this format : ./client 127.0.0.1 portnumber(same as written on server side)


## To communicate with server there are several commands(here are 6 which are implemented in this project):
1. HELO - to start conversation for sending email 
2. MAIL FROM - to send sender's email address
3. RCPT TO - to send recipient's email address
4. DATA - to send data which main content of the email (body part)
5. ATTACHMENT - to send an image file as an attachment with email
6. QUIT - to terminate the connection with server
