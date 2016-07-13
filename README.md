DHAMUN Dev Ecosystem
=========================

## Table of Contents

- [About](#about)
- [Todo](#todo)
- [Creds](#creds)

## About

### General

This is Referendum :)

I'm going to explain what I'm trying to do here, both in technical and non technical terms. Read on.

#### Non-Programmers

Referendum isn't supposed to an MUN app about conference specific information. I built it so people can submit resolutions to chairs easily, and vote on various affairs in neat web-based portal.

Instead of walking to the Chair with a USB drive, you could simply pick the resolution straight off your Google Drive (in Referendum), and have it submit straight to the Chair.

Instead of counting an unclear vote, you could vote on Referendum itself, and get a person-by-person view of how voting has played out (Pass/Reject/Abstain) 

```
a) A web client (started)
dhamun.github.io - This will be a portal for users.
b) A server (coming soon)
This will be a server to which all MUN users will connect. 
c) A mobile app (coming soon)
This is the final step. A mobile portal.
```

### Programmers

Read the non-programmers section. Then come back here.

The web client is built on React, and follows Flux patterns using somthing called Redux. It's an alternative to MVC app structures.

It has hotloading, uses React-Router (I can hear you cackling with joy), and has tests. (Not so many now :p)

The server will run on Node.js, and will use MongoDB as a database.

The app will use React Native. 

### Contributing

Take a good look at the [contributing guidlines](https://github.com/DHAMUN/About/blob/master/CONTRIBUTING.md)

### TODO
1. [X] Simple Website  
A simple landing page. 
2. [X] Simple Server  
A server for Referendum. This is where all Referendum based applications will connect. It will power (potentially) a mobile app, a web portal, etc.
3. [ ] User Accounts  
Create user account services. Let people make their own Referendum accounts instead of signing up with paper and pencil
4. [ ] User Dashboards  
Allow users to view personalized information about the conference, based on their assigned country.
5. [ ] Admin Accounts  
Add support for admin accounts too. Similar to user accounts
6. [ ] Admin Dashboard  
A powerful hub for Referendum admins. Allows them to manage and view user stats, and automagically assign countries
7. [ ] Online Resolution Submission  
Remove the need to carry a USB in the conference. Build Google Docs intergration into user accounts, and let them submit a resolution by selecting a doc in their google drive.
8. [ ] Live resolution vote tracking  
Use dynamic charts to graph the votes for every resolution live, as people vote. Filter charts based on school, etc
9. [ ] Basic Mobile App  
Transition some of the above to a mobile app
10. [ ] Geolocation attendance.  
Use the geolocation sensor on a device to mark a student as present in a  Referendum meeting
11. [ ] @dhamun.com email addresses?????  
As cool as it sounds :p  
12. [ ] Brainstorm more!
