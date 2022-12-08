# Realtime Twitter API App

## Why not $DOGE?

This small & simple, but powerful application utilizes the Twitter API to continuously search for and return any tweet containing the hashtag #dogecoin, and displays them on a SPA. App is deployed online via Render.

Render Deployment Link: [Live Site](https://doge-tracker.onrender.com/)

This application uses socket.io to pass information that the Node/Express backend server recieves from Twitter's API to the vanilla front end. It then renders this data to the DOM as tweets happen in real time. The API is requested via Needle.

Some minimal styling for the tweets has been added via Bootstrap.

Also, I made the sweet header svg image myself in Adobe Illustrator, because I have many talents. :)

This project is based on a project by Traversy Media, and customized by me.

## Technologies

Javascript  
HTML  
CSS & Bootstrap    
Node.js & Express backend  
Socket.io  
Twitter API  
Needle  
