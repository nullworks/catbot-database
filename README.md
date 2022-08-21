# catbot-database
A database for catbot Walkbot paths, custom configs, etc.

Be sure to put you nav meshes into your /tf/maps/ folder.

Configs may be out of date.

## Automated Nav Mesh install
```git clone --recursive https://github.com/CatholicGod/catbot-database;cd catbot-database;sudo cp -R nav\ meshes/* ~/.steam/steam/steamapps/common/Team\ Fortress\ 2/tf/maps;sudo chmod 755 -R ~/.steam/steam/steamapps/common/Team\ Fortress\ 2/tf/maps;cd ..;sudo rm -r catbot-database```
This will clone the repo, install the nav meshes, and remove the repo again.
