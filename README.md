 # Live Demo - https://work-abroad.herokuapp.com/

To run you need to create config file in client dir with GoogleApi key and server URL

In client dir: 

npm init
npm run build

Take build folder and move to the server dir (by default is ignored)
Then in server dir:

npm init

And one of the following commands in server dir:

node app.js
nodemon app.js
npm start


Or you could run concurently both React and NodeJs servers.
