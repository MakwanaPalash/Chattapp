
# Chattapp

 Purpose
The purpose of this project is to design a chat application, also known as a instant messaging 
system. The main purpose of the software is to provide users with an instant messaging tool 
that has the ability to handle millions of users simultaneously when needed and can be easily 
done.

Scope
The application is designed as a web application. It provides a general architecture for chat 
applications, and anyone or organization can use it as the basis for providing instant messaging 
capabilities. The application is written in an object-oriented language called Java.

Overview
This project provides the instant communication functionality between users. The users have 
the capability to do one to one communication, group communications and video/audio chat. 
And the users can receive messages instantly while online and still be able to see the messages 
sent while they are offline. The client-side application can be hosted on any machine with JVM. 
And communicate with server side with socket.

## API Reference

https://www.youtube.com/watch?v=b1bGrWrx5Mo&t=2s
https://www.youtube.com/watch?v=gaykE36N7PY
https://www.youtube.com/watch?v=8Pv96bvBJL4&t=5095s
https://firebase.google.com/docs/auth/web/password-auth
https://firebase.google.com/docs/auth/android/google-signin

## Abstract

Chat application is a feature or a program on the Internet to communicate directly among 
Internet users who are online or who were equally using the internet. Chat applications allow 
users to communicate even though from a great distance. Online Chat Application, as described 
above, can lead to error free, secure. reliable and fast management system. It can assist the user 
to concentrate on their other activities rather to concentrate on the record keeping. Thus it will 
help organization in better utilization of resources. The organization can maintain 
computerized records without redundant entries. That means that one need not be distracted by 
information that is not relevant, while being able to reach the information.
## System Requirement

Functional Requirements
The following are the functional requirements of the system:
 The system shall provide the user the ability to create a new account.
 The system shall provide the user the ability to login with the username and password
 chosen at the time the account was created.
 The system shall deliver sender’s message to receiver instantly if the receiver is 
online.
 The system shall deliver sender’s message to receiver once the receiver is back online 
the message was sent when receiver’s offline. 
 The system shall present the sender’s message to all other users in the group if the
 message is sent to a group.
 The system shall allow multiple users chat in one single room.
 The system shall allow user to talk via video.  The system shall allow user to talk via audio.

 Non-Functional Requirements
The following are the Non-functional requirements of the system:
 The system shall be a web-based application that can provide all the functions over
 the internet.
 The system shall deliver messages in the same order it gets sent out.
 The system shall guarantee the delivery. And shall notice sender if message is not
 delivered successfully.
 The system shall be scalable and robust.
 The system shall be cost efficiently. It shall not cost a lot if there is not many users.
 The system shall deliver the message relatively quickly
## Database Requirement

Firebase is used to store all the information we want to keep, especially data that does not need 
to be changed frequently, such as user authentication and authorization information, such as 
username, password. There is also information such as user friend relationships. Connecting 
and reading the database is time consuming because the database needs to read and write from 
disk. Therefore, the project uses the in-memory database REDIS to use both storage and 
caching. REDIS provides storage for key-value pairs. It rarely reads and writes to the database, 
and most of the time it performs data operations in memory, which saves a lot of time and 
greatly reduces the response time of the application. Key-value pair structures can also speed 
up data lookups