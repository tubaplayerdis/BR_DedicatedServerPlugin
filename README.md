# BR_DedicatedServerPlugin
Downloads for the BR_DedicatedServerPlugin

## BRICKWORKS
 - This mod uses [brickworks](https://discordapp.com/channels/310614354112413698/1544753869790384128) for loading. See install directions

## SETUP (Dedicated & Headless Only)
To have your server show up, ports `7777` and `27015` need to be open and forwarded on your router to your machine.

## INSTALL
BR_DedicatedServerPlugin works exclusively with [brickworks](https://discordapp.com/channels/310614354112413698/1544753869790384128)

 - Download and Install [brickworks](https://discordapp.com/channels/310614354112413698/1544753869790384128) If not already done
 - Download your wanted plugin type
 - Place in `steamapps/common/BrickRigs/brickworks` directory.

Multiple `BR_DedicatedServerPlugin` files will **NOT** work at the same time!. Something will break.

### Plugin Types
 - #### Dedicated
     - Registers your server as dedicated
     - Enables the UE console (F2)
     - Enables & Redirects UE Console output
     - Requires forwarded ports
 - #### Headless (Meant to be used with a headless client ONLY)
     - Registers your server as dedicated
     - Attaches to an existing console
     - Enables & Redirects UE Console output
     - Allows sending console commands through windows console
     - Requires forwarded ports
 - #### Spoof
     - Your server shows up in the regular server list
     - Server has the dedicated server icon
     - Enables UE Console (F2)
     - You do not need to port forward
