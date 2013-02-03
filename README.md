intranetscrabble
================

An app for MozillaOS, name-FIREWORD, that basically can be referred to as an INTRANET scrabble game.

We have used Node.js for the real time playing of the game and HTML5 for the layout.

Users can connect to a common server and choose the opponents among the others.For the Dictionary, right now we are using the default list of words stored in linux.

As of now, there is only one server and as many players can play simultaeneously on the same board.
And the points are given only on the basis of length of the word.
There's an option of chat also, for the users.

What we plan to do in future:

->Create more than one server, so that there can be something like different rooms for playing the game and the user can
select the room he wants.

->Integrating with the cloud, so as to store user's meta-data on the app,like his favourite servers 
and the pending games. 

->Include the various points features for diffrent positions of the boards and for different alphabets.

->Integrate the facebook data like user's friends on facebook, so that user can invite them to play.


How to run:

1.You need to install node.js on your system.

2.install the socket.io and express node modules, using npm install.

3.In the node folder, place the app1.js.

In the app1.js, you need to replace the connecting address with your system's ip and make sure you set the port number as 8082.

4.place the res folder also in the node folder, containig the index.html file and the dictionary.

5.now, go to terminal. change the directory to the main node directory.run the command:

node app1.js

it will start running.

6.go to your mozilla browser and open the stimulator page.

in the add new app section enterthe url as "your ip:8082".

that's it.


we are also providing the whole node folder in case you need :)
