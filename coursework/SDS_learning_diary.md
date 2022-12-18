#### Lappeenrannan teknillinen yliopisto ####
#### School of Business and Management ####
#
#
#### Sofware Development Skills ####
#### Kari Räsänen, <Insert student number here> ####
#
#
# LEARNING DIARY, FULL-STACK MODULE #
#
#
#### LEARNING DIARY ####

**18.11.2022**
Started getting familiar with the platform used to learn. Logged in to moodle, made public bitbucket
repository, and started to get familiar with Full-Stack course. Started watching Node.js Crash Course video.

**19.11.2022**
Finished with Node.js Crash Course video, eager to get my hands on, but trying to hold the horses
and get the basics learned properly. Been used to Android Studio but choosing VS Code as my editor
as it seems to fit better with Node.js. SourceTree seems not to have Linux version,
so skipping that optional tool. Starting getting familiar with MongoDB.

**20.11.2022**
Continued with MongoDB, installed it into own Linux Ubuntu machine and did trials with
the command line. Also installed Compass to see databases. Having been used to relational databases,
this looks very promising! Started ExpressJS course and followed it by coding the same thing alongside.

**2.12.2022**
Refreshed course goals and got an idea to change old PHP based implementation of my website
https://zmengames.com into using MERN stack. It could be the final exercise of the course for me.
Asked from the course directors if it is ok, and it was. Everything else than the actual website
will be public on this repository.

Started studying MERN stack with the youtube author that also videoed the MEAN stack course. Git init
as first step. Made a simple MERN barebone stack to be used in the project. zcarRoutes will be used
to post and get laptimes of the game. Added middleware to router in order to see the request urls.

As the game database is MySQL, used PHPMySQLAdmin to export MySQL database to JSON format, knowing
that MongoDB is almost like JSON (BSON vs. JSON). It was correct assumption as MongoDB compass had
directly tool to import JSON data into databases collections. Now there is 322MB of real players car
racing data and 7.78MB of pinballing data in the MongoDB zmengames database.
Uploaded barebone mern-backend to private repository in Github. Added some route handling and
error handling. Next step will be to connect to MongoDB.

**3.12.2022**
Added mongodb connection, and created controller and model for zcar-racing collection. ZCar sends
params as query parameters, now zcarController in backend returns laps based on query parameters, all imported
data seems to come through fine. ZCar uses android webview to show laptimes, need to fiqure out 
how to output full web page with laptimes for the game. Sending laptimes with ghost lap data from the
game now works through setLaptimes method in zcarController.

**9.12.2022**
Learn about JWT JSON Web Token authentication through the video. Added Login and Register 
functionality into backend. Passwords are hashed with bcrypt. Tested them with Postman, 
now it is possible to register, login and use jwt token to authenticate user.

**12.12.2022**
Started frontend page. Simple login and registration page with react redux. Not sure yet 
if zmengames website will need a registration. Maybe just leave it for future usage by just leaving
the header component containing the login and registration out of the final page. 

