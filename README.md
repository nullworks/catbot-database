# Nav meshes for Catbot.
A database for Navbot paths Fork a catbot-database to fix issue pathing form cathook.

Be sure to put your nav meshes into your /tf/maps/ folder.

## Automated Nav Mesh install
```git clone --recursive https://github.com/STG7754/Nav-meshes-Cat-bot;cd catbot-database;sudo cp -R nav\ meshes/* ~/.steam/steam/steamapps/common/Team\ Fortress\ 2/tf/maps;sudo chmod 755 -R ~/.steam/steam/steamapps/common/Team\ Fortress\ 2/tf/maps;cd ..;sudo rm -r catbot-database```
This will clone the repo, install the nav meshes, and remove the repo again.
