# Node Hello World

Simple node.js app that servers "hello world"

Great for testing simple deployments to the cloud

## Run It

`npm start`





## Node js Monitoring demo app(manual)

sudo apt-get update -y
sudo apt-get install nodejs -y
sudo npm install -g pm2
cd src/
npm install
sudo pm2 stop server.mjs
sudo pm2 start server.mjs
