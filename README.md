# Aim:
Amnis aims to create a live lecture client for students and professors to have a more interactive and engaging learning experience. 

# Features:
The program has 2 standout features. The first being a discussion/chat section where students can ask questions regarding the lecture no matter where they are. The chat runs on a Node.js server as well as a MongoDB database to store previous questions and chat messages. The second feature is live tags. Live tags are generated using Google’s speech to text and NLP API. From the professor’s live mic the audio is analyzed by the API to find keywords. Those words are then put through a database and sorted based on frequency. The words are then transcribed into a text file and displayed as buttons. These buttons can be clicked and it will take the student to a Wikipedia link with additional info about the tag.

# Future Plans:
We hope to bring Amnis to classes throughout our campus. We plan on bringing elements from current webcasts classes use onto Amnis so that switching to Amnis can be a nice and easy transition. In addition to adding features from other similar services, we plan on adding an upvote button for comments, so that professors can view and address questions that students are most confused about. 


# Technologies Used:
- Node.js
- MongoDB
- Javascript
- Websockets
- Jquery(AJAX)
- HTML
- CSS
- Python
- Google Cloud Platform API’s

# Demonstration:
 https://www.dropbox.com/s/uy0pgb5k1xofh79/Amnis_Demo.mov?dl=0
 
 <img width="1280" alt="screen shot 2018-01-21 at 3 30 34 pm" src="https://user-images.githubusercontent.com/26910226/37144280-612775b0-2272-11e8-98ca-3e6770fe438e.png">

<img width="1278" alt="screen shot 2018-01-21 at 3 30 03 pm" src="https://user-images.githubusercontent.com/26910226/37144218-38f8adca-2272-11e8-98d4-891a513ad153.png">

# Installation/Dependencies:
* In order to run the program you must have
- Sockets.io
- Node.js
- MongoDB
- The Google API’s
- Pyaudio



