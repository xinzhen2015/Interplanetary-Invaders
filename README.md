# Interplanetary Invaders

*Computer game where you battle alien spiders across the solar system*

## Installation

Requires:
	
 * python >= 3.7

 * pygame

Installation will also add a ".desktop" file in the Games catagory of your applications

### Installation using pip (recommended)

	pip3 install ii_game

### Installation using pip and git

	pip3 install git+https://github.com/nachomonkey/interplanetary-invaders

### Alternate Installation

	git clone git+https://github.com/nachomonkey/interplanetary-invaders
	cd interplanetary-invaders
	sudo python3 setup.py install

With the alternate install, by keeping the git repo, you can update anytime with a git pull, and optionally build afterwards, or just run:

### Exucution

Run the console script:

	interplanetary-invaders

Or run the "ii\_game" module:

	python3 -m ii\_game

If you did an alternate install run this in the git repo:

	python3 dev\_run.py
	
## Using and playing the game

After launching the game and selecting **Play**, a list of profiles appears. (*These profiles are 
stored in $HOME/ii_game-data/*) Once a profile
is selected, map mode is entered. The **LEFT**, **RIGHT**, **TAB**, **HOME**, and **END** keys are used to navigate
the map. After selecting a mission and continuing through the briefing and inventory mode,
a mission begins. The controls are **LEFT** and **RIGHT** to move (or **a** and **d**) and
**SPACE**, **UP**, or **w** to fire.

At some point you may see an item (![Item](ii_game/images/bitmap/animations/items/block/block1.png  "Item"))
After touching an item, it will disappear and go into your item storage ( ![Item storage](ii_game/images/bitmap/itemHolder.png))
An icon representing the item will be visible in your item storage.
Press the number key on your keyboard that equals the one below the item's icon (i.e. If the item is in slot three, it
will have a "3" under it, and you must press <**3**> to activate it.)  The items vary from mission to mission (and planet to planet)
 
### Hints

When using the "2x Fire Rate" item without the "Auto Gun" item, it is easiest to fire faster
by pressing the **UP** key.

Press **F2** to take screenshots. Screenshots get stored in your *data* directory. The data directory's position gets printed
when the game launches.

# Acknowledgements
Some images (described in the game's credits) were either directly used or modified versions of NASA images.

# License
Uses the GNU GPLv3 License. See the LICENSE file for the full license.