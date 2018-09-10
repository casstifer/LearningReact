# LearningReact
List of projects that I have written while learning ReactJS.

## Cards
WIP

## Food Palace
I made this to learn the concepts of CRUD in ReactJS and to understand how HTML5 Web Storage and realtime database with React works.
<br/>
Usage: Edit 'base.js' file to add your own Firebase API details.

## Polling App
#### Made with React, SocketIO, and Express

##### Usage
Use `npm start` to run the application. This will run the webpack on React source codes in client folder and then run the Express server. Stop and run the server again if make changes to React code base.

##### Known Issues
- When the server restarts, the title doesn't change from disconnected in Speaker component. 
- Question is shown two times in Audience component.
- Sending direct requests to routes causes handing over the control of routing to Express from React Router v4 which results in 'Cannot GET /speaker' output.

##### To-do
- Record the responses.
- Display the data using react-d3 or react-vis.
- Persistent storage.
- Better design and styling.
