# How to run
The app has to be run on a server due to the browser's same origin policy security restrictions. You can simply open the files in VS Code and install Live Server plugin. RIght click on index.html file and select Open with Live Server.

You can also run the app using Node.js http-server.
* Download the files
* In terminal cd to the downloaded directory
* Run commands:

````
npm install http-server -g
````
````
http-server . -p 8000
````

This will serve files from the current directory at localhost under port 8000, i.e in the address bar type: http://localhost:8000/