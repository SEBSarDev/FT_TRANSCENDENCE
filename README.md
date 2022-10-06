# FT_TRANSCENDENCE
First full-stack web application in nestjs and react.

This is a group project, we had to build an application with which we could:
- authenticate using the school's oauth system
- modify our profile (photo, name...)
- add friends
- use a chat with private groups and public groups
- send direct messages
- block users
- temporarily mute or ban users if you are the admin of a channel
- play a game of pong with other users
- watch a match played by other users
and some others features.

We used docker-compose to build are application so it can be launch with a simple 
```
$ docker-compose up --build
```
Unfortunately you can't run this app without the .env but here is some images of what you could find on our application.


![authentification](https://user-images.githubusercontent.com/114223678/194266092-b7a0fc88-3d16-4459-a397-78dd2eb416ef.gif)

Oauth authentification

![addFriends](https://user-images.githubusercontent.com/114223678/194266135-f565f00d-d179-4fb2-8ee6-5fcd086cab91.gif)

Add friends

![ChatDM](https://user-images.githubusercontent.com/114223678/194266189-5f99038e-b904-4e2d-b6f9-c7b9a0789844.gif)

DM

![playPong](https://user-images.githubusercontent.com/114223678/194266213-ae23f11a-468e-4de1-b936-3335c53501cc.gif)

play pong !

![watchMatch](https://user-images.githubusercontent.com/114223678/194266264-3dd1a2ab-fc69-47c4-b219-68140b25d32f.gif)

Watch a match.

![PrivateChan](https://user-images.githubusercontent.com/114223678/194266288-82f1b6ca-c508-4c97-b523-9c47b83716fc.gif)

Create private or public channel, be administrator or owner of channel.

![manyMatch](https://user-images.githubusercontent.com/114223678/194266352-8746203f-997c-45f8-804f-b6683d590ae0.gif)

Many match at same time, watch the one you want.
