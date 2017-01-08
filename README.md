
     ,-----.,--.                  ,--. ,---.   ,--.,------.  ,------.
    '  .--./|  | ,---. ,--.,--. ,-|  || o   \  |  ||  .-.  \ |  .---'
    |  |    |  || .-. ||  ||  |' .-. |`..'  |  |  ||  |  \  :|  `--, 
    '  '--'\|  |' '-' ''  ''  '\ `-' | .'  /   |  ||  '--'  /|  `---.
     `-----'`--' `---'  `----'  `---'  `--'    `--'`-------' `------'
    ----------------------------------------------------------------- 


Welcome to your Node.js project on Cloud9 IDE!

This chat example showcases how to use `socket.io` with a static `express` server.

## Running the server

1) Open `server.js` and start the app by clicking on the "Run" button in the top menu.

2) Alternatively you can launch the app from the Terminal:

    $ node server.js

Once the server is running, open the project in the shape of 'https://projectname-username.c9users.io/'. As you enter your name, watch the Users list (on the left) update. Once you press Enter or Send, the message is shared with all connected clients.






views:
    landing.ejs
    camps.ejs
    new.ejs
    partials:
    
data and what to display on the camps page:


for /camps/new
form with:
    name
    image
    button
once user clicked the button/submit the form, it will go to the /camps page
and display all the camps along with the newly created one
note: difference between GET and POST
GET: to get info from server
POST: to add data to the server 
in order for POST to work, we need another package :
    body-parser
    npm install --save body-parser
    var bodyParser = require("body-parser") ;
    app.use(bodyParser.urlencoded({extended:true})) ;



#part 2: layout and basic styling
1: create header.ejs and footer.ejs in the partials folder
2: get bootstrap CDN and put it in the header.ejs

jumbotron
grid system
thumbnail
display:flex ; flex:wrap:wrap ;
formbutton
navbar
