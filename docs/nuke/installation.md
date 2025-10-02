
###################################################################################################
Installation
###################################################################################################
1. Copy the directory ExchangeNuke to the user's .nuke directory.
2. Add the following to the init.py file in the same directory:
   import nuke
   nuke.pluginAddPath('./ExchangeNuke')
   * If no init.py file exists, you need to create it.
3. Launch Nuke and you should have a "ex" icon in the nodes toolbar.
** There are multiple ways to install plugins for Nuke, this is just an example. A better way would be
   to setup a global plugins directory and use the NUKE_PATH environment variable.