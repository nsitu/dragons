# dragons
Testing out a Nodejs API for Dragons

# installation
git clone https://github.com/nsitu/dragons.git
npm install

# configuration
create a .env file containing mongodb connection string (see .env.example for reference)
setup apache or another proxy to map URLs to the appropriate ports

# running the app from the command line
node app.js

# running the app as a server
install a tool such as pm2 to daemonize the app, then:
pm2 start app.js

# assumptions
assuming you have a mongoDB collection containing pokemon from the Pokemon API

# adaptations
you might adapt this to fit some other kind of data by adjusting the query and projection in app.js
