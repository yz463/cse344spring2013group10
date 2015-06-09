Members : Cihan Ozturk , Oznur Salcioglu, Turhan Arsal

**USER REQUIREMENTS**

•	The users should join the game either a member or a guest .

•	If the user wants to join as a guest , the system should assign a random nickname.

•	If the user wants to join as a member , he/she should sign up using website of the game  giving his/her name,surname,nickname and e-mail address .

•	The users should choose one of the game modes which are single and multiplayer game modes.

•	If the user is guest , the user can play only single game mode.

•	Single game mode includes different types of races against time and computer.

•	Multiplayer game mode provide to race online users which are membership of this game.

•	The users shall select the level of difficulties which are beginner , normal and hard .These levels differ from each other according to properties of maps and density of the traffic .

•	While increasing the level of difficulty , curves on the map increases , also density of traffic increases.

•	The users shall select a car according to level of difficulty of the game and his/her point .

•	If the user is guest , the user shall choose only one low level car .

•	For members :

	Initially every user  has a starting point  .

	User shall select low class car at the beginning of the game .

	When the user gets the points, the system shall open higher class cars , and the user shall buy one of the these higher class cars .

	The user gets the points according to ranking in the race or completing specific tasks .

	The user shall modify the car according to obtained points .

•	The users shall compete each other for his/her points in the game .

•	The users shall compare the points with other members .

•	The system shall gives a ranking for all members on website for competing each other .

**SYSTEM REQUIREMENTS**

•	The system shall have online user sign up/login interface.

o	The system shall assign random nickname for guest.

o	The system shall want to enter nickname , password and email from user who wants to be membership

o	The system shall send confirmation mail to memberships .

o	The system shall have ‘forgotten password’ section.

•	The system shall provide two game modes which are single and multiplayer game modes .

o	In single game mode , the user shall play against time which is determined by the system .

o	The sytem shall choose maps in sequence for single users.

o	The system shall assign the maps randomly for the guests.

o	In multiplayer game mode , the system provides to contact between memberships  .

o	In multiplayer game mode , the system shall allow to participate at least four memberships to start the race .

o	In multiplayer game mode , the system shall allow to membership , that creates a new game , selecting map and lap .

•	The system shall provide three level of difficulty (beginner , normal and hard).

o	In beginner level , the system shall assign straight roads .

o	In normal level , the system shall assign curved roads .

o	In hard level  , the system shall assign spiral roads .

•	In multiplayer game mode , the user shall create a new game  after that the shall select map and lap quantity  . After that other memberships who wants to race this selected map ,he/she connects the game .

•	The system shall offer some options for different type of users
.

o	If the user wants to join the game as a guest , the system shall give only low level car.

o	The system shall give low level car initially for members , when the user increases his/her point , system shall give the members  higher level cars .

o	Every car has some properties : Speed , acceleration and handling . The user shall select the car according to these properties . At high level cars , these properties are better than low level cars’properties .

•	The system shall provide different score options for different type of users

o	The system shall assign specific points to memberships .

o	The system shall show just score for guests and the system shall block collecting these scores for guests .

o	The system shall give points and score to memberships while winning the races and completing the tasks .

o	The system shall determine the tasks .

o	To modify the car , the users shall use the points.

o	The system shall block modifying the cars for guests.

o	The system shall calculate the score for all type of users , but there will be comparison for multiplayer users on the website .

•	The system shall include gallery option which the users shall select and buy cars with own points .

o	The users shall use gallery option as long as his/her points are enough to buy a new car.

•	The system shall include garage option which the users shall modify his/her car (items , colour, tires, engine, nos ,bumper etc.)

o	The users shall use garage option as long as his/her points are enough to modify the car.

•	The system shall provide some hints for users.

o	The system shall give some hints about maps and races to all users before beginning of the race .

•	The system shall have options menu .

o	The system shall provide an option menu to users

	Option part shall include language , sound ,display ,keyboard  etc .

	The user shall change the options with own desire .

**DOMAIN REQUIREMENTS**

We shall use SQL database,.NET and Java language with their libraries for this project .

•	SQL Database is held datas which are user information,cars,maps,car items .

•	To design GUI of this project is used Java Language with API .

•	To design website of this project is used .Net language.
This project also include following domain requirements :

•	Dimensionality  - Two-dimensional (2D).

•	Sound/Music  - Games will be able to reproduce sound effects (wav files) as event reactions. Background music (mp3 files) can be associated with game rooms or information display screens.

•	Input handling -  Keyboard only .

•	Networking  -  High scores can be uploaded to and retrieved from a web server .

•	Target Platform(s) -  PCs running Microsoft Windows XP or higher