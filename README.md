Working with node.js 10.10.0 and npm>=6

Install node.js
sudo apt-get install nodejs-legacy

Install npm

sudo apt-get install npm

To upgrade node.js
sudo npm cache clean -f
sudo npm install -g n
sudo n stable

Sometimes you have to copy node executable file to /usr/bin

cp /usr/local/n/versions/node/10.10.0/bin/node /usr/bin

and check the version

node -v

Run in the root of the project

npm install


**Note : You may need to update `host` in `public/js/config.js`, `crmurl` in `public/js/config.js`, `corebosapi` in `public/setup.js`, `url` in `routes/nodeconfig.js` and `type` into prod or demo in `routes/nodeconfig.js` when it's not in localhost.**

Run npm install to install of the node modules. Socket.io project to notify users in Detail or EditView that someone else is working on a specific record
