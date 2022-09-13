<p align="center"><img src="back_start_game.png" height="400" width="800"></p>
<br/>
<h1 align="center">Welcome To Squid-Game!</h1>

## :door: Project Requirements 
 - Devlop a Client Server infrastructure.
 - Choosing a subject for development which requires a multiple clients.
 - Server controlling on the clients, create & close.
 - Creating GUI using python libaries.
 - Creating some log file in the server, depended on the subject.

<strong> Developing a game based on the doll scene from the squid games "Red Light Green Light" is the chosen subject. </strong> 
<br/>
__________________________________________________________________________________________________________________________________
## :information_source: About 
Squid Game is a South Korean survival drama television series created by Hwang Dong-hyuk for Netflix. 

The series revolves around a contest where 456 players, all of whom are in deep financial hardship, risk their lives to play a series of deadly children's games for the chance to win a ₩45.6 billion (US$35 million, €33 million) prize. 
<br/>

## :space_invader: Modules
### client_server 
<strong>Server:</strong>
- Create server.
- Connect server to network.
- Open a connections for each client.
- Create a different 'get thread' for each client (to avoid 'unblocking design' on the server side) and sharing the packets with all the clients.
- Send packet to all clients.
- Close server (will close all the clients). 
- Get the number of a "live clients".
- The Server have a "listener" (Known as: Design Pattern 'Observer' or Callback), In the case a packet received the listener will get packets & errores from server's threads.
<br/>

<strong>Client:</strong>
- Connect client to network.
- Create 'get thread' for getting server packets.
- Send packet to Server.
- Close. 
- The Client have a "listener" (Known as: Design Pattern 'Observer' or Callback), In the case a packet received the listener will get packets & errores from client's threads.
<br/>

---------------------------------------------------------------------------------------------------------------------
### Business account
- Create your own bars.
- Upload posts.
- Create tables.
- See bar orders.
- Update bar details.

## ⚙️: Tools & Libraries
- Real Time Firebase - DB on cloud
- Storage Firebase - upload photos & videos on cloud
- Authentication Firbase - for making user with providers like phone and google
- Google Maps
- Glide - get photos from cloud Easily
- Lottie - make your on animation 
- Gson 
- Image Picker for upload photos

## :iphone: App Screens
### :calling: Login
- lottie animation
- fire base authentication & UI

|Lottie animation|Authentication by google|Authentication by phone number|
|---|---|---|
|<img src="https://media.giphy.com/media/R4AJsqt466ysE6D1EO/giphy.gif" alt="animated"/>|<img src="https://media.giphy.com/media/MpQ2gxbeIiYzi7Wii3/giphy.gif" alt="animated"/>|<img src="https://media.giphy.com/media/GGxoOJNQOkKpMOoJW0/giphy.gif" alt="animated"/>|

### 💃 Private Account
- Upload photos using Image Picker
- Search engine
- google maps - find location by address
- Calender - you can get date or time from user

|Home page|Google maps|Search Engine|
|---|---|---|
|<img src="https://media.giphy.com/media/1O7hkrPEDXVWsWwxBa/giphy.gif" alt="animated"/>|<img src="https://media.giphy.com/media/k5mfcFpYSpWRowsUpa/giphy.gif" alt="animated"/>|<img src="https://media.giphy.com/media/hcfXtHdeXM7fYXM8n6/giphy.gif" alt="animated"/>

|Make Review|Search page|Profile page|Reservation|
|---|---|---|---|
|<img src="https://media.giphy.com/media/ft3nsXBNr740EJZgYK/giphy.gif" alt="animated"/>|<img src="https://media.giphy.com/media/H9ywaDxnJ1SxwtmGXe/giphy.gif" alt="animated"/>|<img src="https://media.giphy.com/media/a14Z5ys9IKUy2jL7tn/giphy.gif" alt="animated"/>|<img src="https://media.giphy.com/media/r65IN7S5jU9YHX0DU8/giphy.gif" alt="animated"/>

### 🍹: Business Account
|Home page|Bar page|Tables & Ordres|
|---|---|---|
|<img src="https://media.giphy.com/media/5h9RTI05Hmv1iDACAh/giphy.gif" alt="animated"/>|<img src="https://media.giphy.com/media/0KvyBJgiodaxMQGhfh/giphy.gif" alt="animated"/>|<img src="https://media.giphy.com/media/mEC8JQBXxZIO5TpPWL/giphy.gif" alt="animated"/>|


