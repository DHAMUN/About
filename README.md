DHAMUN Dev Ecosystem
=========================

## Table of Contents

- [About](#about)
- [Todo](#todo)
- [Creds](#creds)

## About

### General

This is DHAMUN Dev.

I'm going to explain what I'm trying to do here, both in technical and non technical terms. Read on.

#### Non-Programmers

DHAMUN is an outstanding conference. It truly is. 
But it's limited. Imagine.

```
Imagine meetings where you didn't take attendance by running 
around with a spreadsheet. People take out there phones and 
mark themselves present, using a geolocation sensor in there phone.

Imagine realtime tracking for resolution votes. 
No need to "tally the house or whatever." 

Imagine submitting a resolution online, and not carrying a USB around.

Imagine DHAMUN virtualized. Let's make this imagination a reality.
```

Now that was nice. The point of this project is to create an ecosystem for DHAMUN, not a simple, pretty website. A hub for DHAMUN staff and members. I've created a client you can check out in another repo. This is the start.

Look at the [TODO](#todo) for future features.

This is DHAMUN Dev. 

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

Open an issue on github. Make a PR that fixes it (if you want). 

### TODO
1. [X] Simple Website  
A simple landing page. This was in my tech manager application. It showcases basic design skills. This is not my strength
2. [X] Simple Server  
A server for DHAMUN. This is where all DHAMUN based applications will connect. It will power (potentially) a mobile app, a web portal, etc.
3. [ ] User Accounts  
Create user account services. Let people make their own DHAMUN accounts instead of signing up with paper and pencil
4. [ ] User Dashboards  
Allow users to view personalized information about the conference, based on their assigned country.
5. [ ] Admin Accounts  
Add support for admin accounts too. Similar to user accounts
6. [ ] Admin Dashboard  
A powerful hub for DHAMUN admins. Allows them to manage and view user stats, and automagically assign countries
7. [ ] Online Resolution Submission  
Remove the need to carry a USB in the conference. Build Google Docs intergration into user accounts, and let them submit a resolution by selecting a doc in their google drive.
8. [ ] Live resolution vote tracking  
Use dynamic charts to graph the votes for every resolution live, as people vote. Filter charts based on school, etc
9. [ ] Basic Mobile App  
Transition some of the above to a mobile app
10. [ ] Geolocation attendance.  
Use the geolocation sensor on a device to mark a student as present in a DHS DHAMUN meeting
11. [ ] @dhamun.com email addresses?????  
As cool as it sounds :p  
12. [ ] Brainstorm more!

### Creds
1. Fuzzy and Shan masala for telling me 'bout "Tech Manager"