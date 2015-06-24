
Changed the original Succinct theme with some color tweaks of my own, reducing contrast. Also
added two variants, Solarized and Solarized Dark, based on http://ethanschoonover.com/solarized.
Nickname coloring comes courtesy of [willasaywhat](https://github.com/willasaywhat).

Default:

![Screehnshot](Default.png)

Solarized:

![Screenshot](Solarized.png)

Solarized Dark:

![Screenshot](Dark.png)

Download & Install Instructions:
--------------------------------

If you're finding this theme by google and don't really know what you're doing, you're
exactly like me when I found the original. Steps to download:

1. To the upper right, there's a button called "Download ZIP". Download and unzip it.
2. Move all the contents of the folder except "Succinct.colloquyStyle" to the trash. You don't
need them. 
3. Open an additional Finder window and, from the Finder's "Go" menu, select
   "Go to Folder..." . In the dialog pane that appears, enter:
     /Library/Application Support/Colloquy/Styles
4. Drag "Succinct.colloquyStyle" there.

Restart Colloquy or type /reload styles into Colloquy.

Editing Instructions:
---------------------

Again, when I found the original theme, I wanted to change a lot of the features myself,
beyond what Colloquy allows you to do in the preferences menu. Here are instructions to tweak
the themes to your liking if you've already download them.

1. Locate the file. (Open a Finder window and, from the "Go" menu, select "Go to Folder..."
and enter: /Library/Application Support/Colloquy/Styles
2. Right click "Succinct.colloquyStyle" and select "Show Package Contents."
3. Navigate to Contents -> Resources.
4. To change colors in the default theme, edit Main.css. To change Solarized colors, double click
the folder labeled "Variants."
5. The CSS files inside this folder are clearly labeled and ready to edit.

I used [this website](http://www.w3schools.com/tags/ref_colorpicker.asp) to pick colors.

----------------

Colloquy (<http://colloquy.info>) is a very nice IRC application for Mac OS X,
but its included chat styles are in need of some serious design and usability
work. Succinct is an add-on style that is designed to be the "missing style" for
Colloquy and is inspired by 37signals's Campfire design, but re-purposed for IRC
communication.


Three reasons to love "Succinct" for Colloquy
---------------------------------------------

1. Simple clean design.
2. Emphasizes what you need.
3. De-emphasizes what you don’t.


Contributors
------------

* Claudio Perez Gamayo <http://80kv.com>: Created first-draft design based on 37
  Signal's Campfire web application.
* Joel Watson <https://github.com/watsonian>
* Willa Riggins. <https://github.com/willasaywhat>

Additional bugfixes, usability improvements, and design comments are welcome!
Just use GitHub to fork and make pull requests.

<https://github.com/JohnAlbin/succinct-for-colloquy>
