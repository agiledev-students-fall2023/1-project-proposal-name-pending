# Project Proposal 1

## Collaboration
Jason Zhang (sz3042)

### Project title
Athena's Music Ranking System

### What and Why?
I'd like to build a music ranking system that would allow users to rate the album and/or songs within an album. This system would provide a fun way to explore the users' music tastes as well as being able to connect with their friends to show them their thoughts on the music. This would allow for users to take part in the ranking and critiquing of music instead of it being solely restricted to music critics and publications. 

### For Whom?
The software would be geared towards the mass consumer and people like me, specifically the teen and early adult demographic. Especially those that find themselves enjoying tier lists, listening to music, and/or have a passion for music. This would allow them to connect more with friends as well about common interests.

### How?
The app will function like Letterboxd or beli; an end-user will search up an album from an artist and be able to give the album a review as well as rate it out of 5 stars. The user will also be able to relog the album if their thoughts change. They will also be able to click on the album and rank the songs on the album according to their tastes i.e. 1 through n. The app will then keep a "diary" log of the albums that have been rated by the user. The user can choose some albums and favorite them. The user can also follow and unfollow other users.

### Scope
This system will rely on accessing a large, constantly updating music database (Spotify API??) and integrating a multi-leveled rating system. The usage of various, complex data structures will provide a difficult challenge to get all the information displaying correctly across various windows. It will also be a challenge to have an instantaneous updating database of users to follow and unfollow. However, this project could prove to be an enriching experience to learn how to work with open databases and create a usable social netowrking software.

# Project Proposal 2

### Project Title
Richards TV Project

### What and Why?
The idea is to create a way for people to recieve recommended TV shows based on what they have watched and what platforms they have access to. This way, people can recieve recomendations for new TV shows that they might enjoy. Later, they can give feeback regarding if the recommended TV show was enjoyable or if it wasnt and based on this they might recieve a new reccomendation.

### For Whom?
This idea would be primarily for people who enjoy watching a lot of TV shows, especially of a particular genre. While all ages watch TV, it would mainly be used for the 15-30 age range or those who have a lot of access to streaming platforms such as Netflix and Disney etc. 

### Step Through
User would input a specific tv show that they enjoyed and wanted something similar. They would then recieve a new TV show that is relatively close to what they asked for. After watching the TV show, the user can come back and give either a positive feedback ro a negative feedback based on if they enjoyed it or not and then the system will give a new recomendation.

### Implementation
First, it would be useful if there was a databse of most of the TV shows. This way, people can do a search and add the tv shows that they have already seen so that we know what to give them a recomendation based on. Next, it would be neccesary to use a api to recieve TV shows that are close to what the user is asking for. We would also need to use a databse to ensure that our reccomendation is not something that has already been seen/given. Unfortunatly, I am not sure if there are any APIS that are useable to recieve the tv recomendations.

# Project Proposal 3

### Project title
Angela's qr code generator

### What and Why?
The idea is to have an app that each user can login and save all the social media credentials and personal informations into one QR code. When others scan the code, it will show all personal information the owner of the QR code wants to share. This makes networking easier which people can just show their QR codes and can then automatically save all the contact informations.

### For Whom?
This app can basically be used by anyone who is willing to share their contact informations and social media ID accounts to others.

### How?
When user log in, they will be asked to add personal informations. These persoanl informations would include stuff like Facebook account, Linkedin, Instagram, phone number, and emails etc. The user will save all these informations in the personal page, and these credentials can be selected to be add into the QR code. Then the user can generate QR code based on the informationthey willing to save into the QR code. 

### Scope
The app would need a database to store each users login information, and seperate database for each users informations. It will also need a QR code generator(e.g.ZXing Library) for the QR code generation, and then a separate database to store the QR codes.

# Project Proposal 4

### Project Title
Janet's Plant Repository

### What and Why?
An app/web page that allows a user to document their plants and look up proper plant care.

### For Whom?
Mainly for those who like to take care of plants (plant moms) although it may be a good app for people just starting to get into gardening/plants or someone who may not know how to take care of plants and is learning.

### How?
Needs a login and registration - afterwards should take you to a dashboard where you can look up and add plants to your account. Added plants should have some information that can be included, as well as a place for the user to continue documenting the plant progress.

### Scope
A database that can store user's registration, and seperate database for any plants that the user will add. Potential UI/UX design for interactive features, as well as features for search and documenting plant information (from another database or creating a new one).
