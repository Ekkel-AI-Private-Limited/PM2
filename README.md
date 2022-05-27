# PM2 Process Manager

## Installation Guide:
   1. curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
   2. sudo apt-get install -y nodejs
   3. sudo npm install pm2 -g
   4. pm2 ls
   
## How To Use:
   1. pm2 startup (Copy the last startup response line and run it to save settings to bash script)
   2. Now create a pm2.config.json file.
   3. pm2 start pm2.config.json
   4. pm2 save

## To Access Port 80 Without Root
![image](https://user-images.githubusercontent.com/63394104/156816911-4590bd2d-4420-45b5-bc1f-7cf75d54b1b7.png)
