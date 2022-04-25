# Welcome to: CSS Club Chat Portal

<img src="https://i.imgur.com/ZE6tTFI.png" alt="drawing" style="width: 100px; height 100px;"/> <br>Chat Portal

## Table of Contents
- [Website Description](#Website-Description)
- [Website Background](#Website-Background)
- [CSS Club Github/Website](#CSS-Club-Github/Website)
- [Website Technology](#Website-Technology)
- [Website Features](#Website-Features)
    - [Register View](#Register-View)
    - [Login/Logout View](#Login/Logout-View)
    - [Home Page View (3 Sections)](#Home-Page-View-(3-Sections))
        - [Browse Topics (Left side)](#Browse-Topics-Left-side))
        - [All Rooms (Middle)](#All-Rooms-Middle)
        - [Participants Feed (Right side)](#Participants-Feed-Right-side)
    - [Create/Update Room View](#Create/Update-Room-View)
    - [Profile View](#Profile-View)
    - [Search Functionality](#Search-Functionality)
- [Django Admin Panel](#Django-Admin-Panel)
- [Future Features](#Future-Features)
- [Wrap Up](#Wrap-Up)
- [License](#License)


## Website Description
<p>
    Hello 👋, my name is Leandro Gamarra. Welcome to my newest Website Application, Chat Portal. Chat Portal is a chat based Django application where users will be able to login/logout/register and able to create Chat rooms. In these rooms, Computer Science Society Club (more info below) members/users will be able to chat amongst each other depending on the topic that the room is for. Moreover, users will also be able to edit their own profile and update/delete any messages they have sent or chat rooms they have created. Read more below to learn about all of the website's features.
</p>

## Website Background
I began this website during the Spring semester of 2022, specifically during my Spring Break. What led me to begin developing this Website, was that I saw that at the Computer Science Club at my college, in which I am it's current President, that many club members didn't like using Discord. For reference, Discord is the main source of communication between Club executives and members and it's where we post any club Announcements and upcoming events. Therefore, I thought, why not create a website that is much more user friendly and will achieve all the most useful features from Discord? Hence, the final product for a Discord alternative for the members of the CSS Club is below.

## CSS Club Github/Website
Like I mentioned above, here are the links for my clubs [Official Computer Science Society Club Website](https://jjaycss.tech/) and [Github Organiztion Account](https://github.com/jjcss) that we use to connect and communicate with other club members.

## Website Technology
- Front-end: HTML/CSS (Static)
- Back-end: Django (Python)
        - SQLite
        - Authentication (Login/Logout/Register)
        - CRUD System
        - Data Persistence
        - Django Admin Panel
- Git/github

## Website Features

### Register View
- <b>Register View</b>: is where new club users come and make a brand new account. <br>
        - Newcomers to the website will be able to see all current chat rooms/messages and participants (users), but they won't be able to send messages or create new rooms: <br>
            - <img src= "https://i.imgur.com/ABtrEVq.gif" style="width: 700px; height 400px;"> <br>
        - Next, once the user decides to make an account, they are taken to the registration view. <br>
            - <img src= "https://i.imgur.com/jjPAcbl.gif" style="width: 700px; height 400px;"> <br>

### Login/Logout View
- <b>Login View</b>: after a user has created and account, they'll be able to log back in and logout. <br>
        - Here is a quick view of the Feed View: <br>
            - <img src="https://i.imgur.com/QKGo3qZ.gif" alt="drawing" style="width: 700px; height 400px;"/> <br>

## Home Page View (3 Sections)

### Browse Topics (Left side)
- The user will be able to see the top 5 Topics that are currently made (5). Depending on a topic, the user will be able to see any rooms that are related to that topic and as well as any messages in that specific topic. <br>
        - <img src="https://i.imgur.com/BRCkjBb.gif" style="width: 700px; height: 400px"> <br>
        - The user will also be able to go to another view, that will display all topics, since the main room ony displays the top 5. <br>
        - <img src="https://i.imgur.com/7hYNZ51.gif" style="width: 700px; height: 400px">

### All Rooms (Middle)
- The user will be able to see all rooms currently available. Each room displays the room name, description, how long ago it was created (who the host is) and how many people have joined. The user can also click on each room and in there the user can join the room and begin sending messages. <br>
        - <img src="https://i.imgur.com/pI58wWI.gif" style="width: 700px; height: 400px">
- If the user joins a new room and sends a message, they'll be automatically added to the participants list in Chat View. <br>
        - <img src="https://i.imgur.com/b3dH89x.gif" style="width: 700px; height: 400px">

### Participants Feed (Right side)
- In the home page, the user will be able to see any recent activities by any users on the website. Such activities, include any new messages that users post in rooms. In the feed, you'll also be able to delete any messages if you are the owner of the message. <br>
        - <img src="https://i.imgur.com/vR4fyGq.gif" style="width: 700px; height: 400px">

### Create/Update Room View 
- <b>Create Room</b>: Users will be able to create new rooms and choose a topic, room name, and add a description.<br>
        - <img src="https://i.imgur.com/0r056El.gif" style="width: 700px; height: 400px"> <br>
<b>Update/Delete Room</b>: Users will also be able to update a room that they made. They can also delete their room if they'd like.<br>
        - <img src="https://i.imgur.com/WKjocKA.gif" style="width: 700px; height: 400px"> <br>
        - <img src="https://i.imgur.com/h8nHlQs.gif" style="width: 700px; height: 400px">
        
### Profile View 
- <b>Profile View</b>: Users will be able to go to their profile view and add/update their bio, user image, name, password, and email. Their profile view will also display any of their recent activities and any rooms that the user created, if any. <br>
        - <img src="https://i.imgur.com/TGiWL9c.gif" style="width: 700px; height: 400px">

### Search Functionality
- <b>Search</b>: The user will be able to use the search bar in the navigation bar to find select rooms, or select topics.<br>
        - <img src="https://i.imgur.com/N9s4RiO.gif" style="width: 700px; height: 400px">

### Django Admin Panel
- <b>Django Admin Panel</b>: The user will be able monitor any messages, topics, rooms, and users via the admin panel that Django provides. Also, this is where all user data is stored using Django's SQLite database<br>
        - <img src="https://i.imgur.com/6KA2oRH.gif" style="width: 700px; height: 400px">

## Future Features
In the future, I would like to deply this website and connect it with the [Computer Science Society Club Website](https://jjaycss.tech/). I am in the process of conneting them two since I would really like to give the club members an option to communicate in our very own website, rather than on our Discord server. Furthermore, I'd like to add in features where the user will be able to add images to their messages and the ability to follow other users. Overall, I'm content with what I have right now.

## Wrap Up
I hope you enjoyed my project. I'll continue working on it.


## License
Copyright [2022] [Leandro Gamarra Montero]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
