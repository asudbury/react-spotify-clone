# Spotify Clone Front-End
A front-end clone project of the Spotify web player. The project was created using the create-react-app CLI. The app is meant to work in conjunction with an authorization/authenication server found at this [repo](https://github.com/JL978/spotify-clone-server).

## Table of Contents
- [Description](#description)
- [Motivation](#motivation)
- [Tech/Framework Used](#techframework-used)
- [Installation](#installation)
- [Architechture](#architecture)

## Description
A clone web application using the create-react-app. The app comsumes data from the Spotify API and tries to mimic the UI and front-end behaviours of the official [Spotify web player](https://open.spotify.com/) as much as possible.

![App Screen Shot](https://github.com/JL978/spotify-clone-client/blob/master/demo/FrontPage.png)
*The main screen (non-authenicated) of the app*

Like the official app, if a user is not authenticated, they can still browse and look up different playlists, albums, artists and users. Non authenticated users cannot control the player and go to certain protected routes - if they tried to navigate to these routes, a tooltip pops up prompting login.

![Non-authenticated app demonstration](https://github.com/JL978/spotify-clone-client/blob/master/demo/NonAuthed.gif)
*Non-authenticated app demonstration*

If a user login to a premium account (due to the limitation of the available API, free accounts cannot do much), user can access certain routes to their own playlists, saved items, etc. and use the app as a remote control player to any playing official (no direct streaming is available through the API)

![Authenticated app demonstration](https://github.com/JL978/spotify-clone-client/blob/master/demo/Authed.gif)
*Authenticated app demonstration*

![Remote player demonstration](https://github.com/JL978/spotify-clone-client/blob/master/demo/RemotePlay.gif)
*Remote player demonstration*
