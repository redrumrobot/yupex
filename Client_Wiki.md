# How to install #
  1. Download the client binary that fits your operating system
  1. If you are using **Windows**, your old client should be located at C:\Program Files\Tremulous
  1. If you are using **Linux**, your old client should be located at /usr/local/games/tremulous
  1. Once you have located your old client, replace/overwrite it with the client you have downloaded
  1. Start tremulous and take advantage of Yupex's feature!

# How to check version #
  1. Press the ~ key on your keyboard
  1. Look at the lower right hand corner
  1. Compare the version printed with the one on the Home page
  1. If the text printed is lesser than the one on the Home page, please follow the install instructions again to upgrade

# Backported / Fixed #

  * Fixed favorites menu bug (Slacker)
  * Fixed sort by ping (Amanieu)
  * Backported windows home path (Slacker)
  * Backported qkey load location (Mercury)
  * Backported video modes to be compatible with 1.1 UI (Critux)
  * Backported color escape (Mercury)

# Added features #

  * Display black in console correctly (benmachine)
  * Double the max limit on cvars and console text (Mercury)
  * Double the max command buffer (Mercury/doomagent13)
  * Message mode argument (benmachine)
  * TJW style and SVN style cURL compatibility layer (Mercury)
  * vstr helpers (wireddd/Amanieu)
    * **if** - _comparison between cvars_
      * if (variable1) (operator) (variable2) (variablethen) (variableelse)
      * valid operators are = != < > >= <=
    * **math** - _addition, subtraction, multiplication, and division between cvars_
      * math (variableToSet) (variable1) (operator) (variable2)
      * math (variableToSet) (operator) (variable1)
      * math (variableToSet) ++
      * math (variableToSet) --
      * valid operators are + - `*` /
    * **strcmp** - _compare two strings_
      * strcmp (string1) (operator) (string2) (cmdthen) (cmdelse)
      * valid operators are = !=
    * **concat** - _combine two cvars_
      * concat (variableToSet) (variable1) (variable2)

  * Bloom (Harekiet/Mercury)
    * **r\_bloom** - _Enable/Disable bloom_
    * **r\_bloom\_alpha** - _Control the transparency of bloom_
    * **r\_bloom\_intensity** - _Control how much to bloom_
    * **r\_bloom\_darken** - _Control how dark to make the bloom/screen_
    * **r\_bloom\_sample\_size** - _Control how many samples to display_
> > `*` the higher this is the lower your fps will be

  * Console visual controls (Mercury)
    * **scr\_conUseShader** - _Enable/Disable shader use_
    * **scr\_conColorAlpha** - _Control transparency of the console_
    * **scr\_conColorRed** - _Control how much red will be painted on the console background_
    * **scr\_conColorGreen** - _Control how much red will be painted on the console background_
    * **scr\_conColorBlue** - _Control how much green will be painted on the console background_
    * **scr\_conBarColorRed** - _Control how much red will be painted on the console bar_
    * **scr\_conBarColorGreen** - _Control how much red will be painted on the console bar_
    * **scr\_conBarColorBlue** - _Control how much green will be painted on the console bar_
    * **scr\_conBarHeight** - _Control the height of the console bar_
> > `*` all color cvars are on a 0 to 1 scale, meaning 1 is full color, 0 is no color, and 0.5 is half

  * Reduce map change spam (Amanieu)
  * VOIP client speaking display (Mercury)
    * **cl\_voipShowSender** - _Enable/Disable the client speaking display_