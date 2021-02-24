# tf2-mvm-serverconfig

My custom configuration for TF2 MVM Server and instructions for PingPerfect.com.

# Steps

1. Open server control panel on Ping Perfect.
2. Go to configuration files and paste the contents of *mapcycle.txt* and *server.cfg* from this repo.
3. Change on server.cfg the hostname an RCON Password.
4. Go Commandline Manager and create your custom commands using the examples from next section.
5. Upload custom maps using the file manager.
6. Go to *Update your server from Steam*.
7. You're ready!

## Custom Commandlines

Example custom command lines to run maps.

* **666** -console -game tf -nohltv -condebug -port 24515 +exec server.cfg +maxplayers 32 +map mvm_coaltown +exec "server.cfg" +map "mvm_ghost_town"
* **bigrock** -console -game tf -nohltv -condebug -port 24515 +exec server.cfg +maxplayers 32 +map mvm_coaltown +map "mvm_mannworks"
* **coastrock (custom map)** -console -game tf -nohltv -condebug -port 24515 +exec server.cfg +maxplayers 32 +map mvm_coaltown +exec "server.cfg" +map "mvm_coastrock_rc1_1"