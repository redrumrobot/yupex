# How to install #

  1. If you are using the stock/TJW backport client then select "**stock-update-vms.pk3**" from the download tab.
  1. If you are using a client that isn't compatible with the 1.1 game QVM, like Tremfusion, or Yupex, select "**update-vms-pk3**" from the download tab.
  1. Locate your base folder, it should be in the same directory as your client binary.
  1. Locate the file "**vms-1.1.0.pk3**" and rename it to "**backup**". If you are upgrading, this is not necessary.
  1. Place the Yupex VM update ("**update-vms.pk3**" / "**stock-update-vms.pk3**") in your base folder.
  1. Start tremulous, join a server, and you should be ready to use the Yupex VM update!

# How to uninstall #

  1. Locate your base folder, it should be in the same directory as your client binary.
  1. Locate the file "**stock-update-vms.pk3**" / "**update-vms.pk3**" and delete it.
  1. Locate the file "**backup**" and rename it to "**vms-1.1.0.pk3**".
  1. Start tremulous, join a server, and your stock VM set should be loaded.

# How to check version #
  1. Start Tremulous
  1. Enter a server, doesn't matter which one it is
  1. Type /cg\_version, compare the set text with the one on the Home page
  1. If the text is lesser than the one on the Home page, please follow the install instructions again to upgrade

# Added features #

  * Cvars
    1. **cg\_chatBalloon** _0|1_ - Display a chat balloon over the head of a player that is typing
    1. **user\_spectating** - Displays name of the player you are spectating( if any )
    1. **user\_hp** - Displays the current health
    1. **user\_maxhp** - Displays the max health
    1. **user\_class** - Displays the current class selection (in integers)
    1. **user\_classname** - Displays the class selection
    1. **user\_weapon** - Displays the current weapon selection (in integers)
    1. **user\_weaponname** - Displays the current weapon selection
    1. **user\_team** - Displays the current team selection (in integers)
    1. **user\_teamname** - Displays the current team selection
    1. **user\_stage** - Displays your team's stage
    1. **user\_credits** - Displays your current credits/evos
    1. **user\_score** - Displays your score
    1. **user\_attacker** - Displays the slot number of the last player that caused damage to you
    1. **user\_attackername** - Displays the name of the last player that caused damage to you
    1. **user\_crosshair** - Displays the slot number of the player in your crosshairs (teammate limited)
    1. **user\_crosshairname** - Displays the name of the player in your crosshairs (teammate limited)
    1. **cg\_placementFix** - Enable/Disable the visual fix for model not matching bbox

  * Other
    1. Smooth mass driver zooming
    1. **calc** - A simple math calculator
    1. **ccp** - Client center print