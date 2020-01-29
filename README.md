# jwtAuthentication
Jwt Authentication and with all basic setups 

Basic Authentication with jwt for admin and user and i have mentioned the packages below for your use.

Packages used in the projects

# jsonwebtoken

  JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs can be signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

Although JWTs can be encrypted to also provide secrecy between parties, we will focus on signed tokens. Signed tokens can verify the integrity of the claims contained within it, while encrypted tokens hide those claims from other parties. When tokens are signed using public/private key pairs, the signature also certifies that only the party holding the private key is the one that signed it.

# Redis

  This is a complete and feature rich Redis client for node.js. It supports all Redis commands and focuses on high performance.
  Used for user socket id save in redis and used for notificarion function
  
# Socket.io

  Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server
  Socket.io used for sever side to send web application notification to  users .
  
# socket.io-client

   A standalone build of socket.io-client is exposed automatically by the socket.io server.
   socket.io-client is used in user side for web application notification .
   
# fcm-node

    A Node.JS simple interface to Google's Firebase Cloud Messaging (FCM). Supports both android and iOS, including topic messages, and parallel calls.
Aditionally it also keeps the callback behavior for the new firebase messaging service.
    fcm-node is used for android side push Notification using device id.

# apn
    An interface to the Apple Push Notification service for Node.js
    apn is used for ios side pushNotification using device id.
    
# express-rate-limit

   Basic rate-limiting middleware for Express. Use to limit repeated requests to public APIs and/or endpoints such as password reset.
   
# ddos

   Configurable Denial-Of-Service prevention for http services





