# CIBGO (CheckInBoardGo)

Cibgo is a trolley-based application aiming to smooth your flying journey. This solution participates in the [Singapore Airlines AppChallenge 2019](https://appchallenge.singaporeair.com/en/challenges/appchallenge-2019). The idea is ,on one hand, to create an app which helps the passenger to perform self check-in and provide all the needed procedures from boarding to landing. On the other hand, a trolley will be integrated with a balance which shows the weight of baggage on the app.

### App

The app applies CS architecture. The client side is written with React Native in order to cover full platform. The server leverages Python Flask to develop.

### Trolley

The new generation trolley will be transformed from a traditional one by adding a connected balance. This balance connects the app via server which is in charge of transfering data from the balance to app in real time.
