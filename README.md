sudo npm install -g @angular/cli@6.2.1
sudo npm install -g json-server
json-server --watch json-server/db.json -d 2000 -p 3000


echo "fs.inotify.max_user_watches=524288" | sudo tee -a /etc/sysctl.conf