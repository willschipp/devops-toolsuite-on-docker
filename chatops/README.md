# chatops

- use rocket.chat as a basis for chatops comms


```docker run --name db -d mongo:3.0 --smallfiles```
```docker run --name rocketchat --link db -d rocket.chat```
