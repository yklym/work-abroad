 # [Live Demo](https://work-abroad.herokuapp.com/)

 ## Description
 Small educational roject done with ReactJs and NodeJs.
 ## Starting App
To run you need to create config file in client dir with GoogleApi key (can be invalid) and server URL:

My config file looks 
   
    export const googleMapApi="--"; //Your Api or any string
    export const serverUrl = "/api/v1";
    export const pageSize = 5; 

In client dir: 

  `npm init`
  
  `npm run build`

Take build folder and move to the server dir:

Then in server dir:

  `npm init`
  
And one of the following commands:

    node app.js
    nodemon app.js
    npm start


Or you could run concurently both React and NodeJs servers. Than ypu need to set up serverUrl in client config as:

     export const serverUrl = `https://localhost:8080/api/v1`;

where 8080 is default port in server/config.js file. Build must be created anyway or you'll need to modify server/app.js.

Than run concurently in both server/ and client/ dirs run: 

    `npm start`
