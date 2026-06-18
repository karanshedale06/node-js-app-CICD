# node-js-app-CICD





sudo apt-get update

sudo apt-get install -y nodejs npm

node -v

npm -v



sudo npm install -g pm2

pm2 -v



clone node-js-app-CICD application



cd /var/lib/jenkins/workspace/02-pull-node-repo

sudo npm install



cd /var/lib/jenkins/workspace/02-pull-node-repo

sudo pm2 start app.js --name node-app|| pm2 restart node app



added security group 3000

