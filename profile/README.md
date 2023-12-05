# AniMatcher

## Team:
- William Zhou
- Philip Yi
- Kelly Huang
- Konnie Huang
- Arnav Jindal 

## Work For Final Submission:

Philip Yi: Created S3 Bucket and Profile Picture Adder Feature. Basically modified UI forms to accept image drag and drop, uploaaded and setup AWS s3 bucket for images. Added endpoints for Anilist OAuth. Created K-NN ML Algorithm. Created SQL Functions to speed up API calls.

William Zhou: Created Swiping Feature. Setup endpoints to fetch matches, store likes and mutual likes. Also Created UI for swipes. Created endpoints for S3 bucket uploads.

Kelly Huang: Created Edit Profile Feature. Ensured all api routes for Edit worked and made profile UI nicer. Edited Swiping UI to look nicer and fixed swiping endpoints to let users know when they ran out of swipes.

Konnie Huang: Created Script to make fake users, made endpoints to handle them. Worked on testing code for bugs and fixing authentication glitches from both UI and backend. 

Arnav Jindal: Created Chatroom Feature. Made page for matches, allowed matched users to create a websocket based private chatroom that worked realtime. Deployed project and setup Docker container on Oracle to speed up web page loading.

## Work:

Philip Yi: Profile API Endpoints, S3-Bucket, O-Auth, Swiping API Endpoints, Matching Endpoints, Chatroom Endpoints, Database API Endpoints, Anilist Endpoints

William Zhou: Login API Endpoints, Swiping UI, Database API Endpoints, User API Endpoints, Swiping API Endpoints

Kelly Huang: Machine learning API Endpoints, Anime API Endpoints, Swiping UI, Database API Endpints, User API Endpoints

Konnie Huang: DBMS set up, User API Endpoints, Automatic data generator script, Supabase CRUD Endpoints

Arnav Jindal: Frontend, Chatroom Endpoints, O-Auth Login, Login API Endpoints, Profile API Endpoints, Anilist Endpoints

## Unique Endpoints:
 A simplified overview of our API endpoints. For detailed documentation visit: https://web-production-df9f.up.railway.app/redoc

- GET /profile: gets user profile for page
- POST /profile: post new user profile
- POST /user: barebones user for Oauth
- GET /user: check if user is new or not
- PATCH /profile:  Edit profile
- POST /user-animes: Add users anime preferences
- GET /user-animes: get a users name
- GET /matches: get a users matches
- POST /like: store when a user swipes right
- GET /mutual-likes: get matches, when both users like each other
- POST /create-chatroom: create chat from mutual likes
- GET /chatroom: get all chatrooms for user
- GET /messages: get all messages for chatroom
- POST /message: post a new message
- GET /anime: get anime with query for anime search

## System Design

We have 3 services.




## Demo Video 

Milestone 3: https://www.youtube.com/watch?v=-GLwvH9KjoM
Milestone 4: https://www.youtube.com/watch?v=KR02sxAYyuI


## Repositories

- [React Native App](https://github.com/AniMatcher/App)
- [Web Frontend](https://github.com/AniMatcher/Web)
- [Backend](https://github.com/AniMatcher/Backend)

## Goals

Sick CS316 Project.
