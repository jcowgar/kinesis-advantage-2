My mappings of the Kinesis Advantage 2 Keyboard
===============================================

I am a computer programmer that has many requirements normal computer users
may not from their keyboard. Thus, I have many remappings and macros for my
Kinesis Advantage 2 keyboard.

I've setup this repository to share them and to keep my settings backed up. Here
you will find many text files performing specific tasks. The Advantage 2 does
not use these files. They are for reference and for building new layers. You
will also find files such as qwerty.txt, 1_qwerty.txt, etc... These files the
Advantage 2 does use directly.

Please visit https://www.kinesis-ergo.com/support/technical-support/manuals-drivers/
for use manuals on what the special filenames are.

invert-number-row.txt
---------------------

After analyzing the text of my source code repositories I found that I use the
special symbols on top of the numbers much more than the actual numbers. Thus,
why make those require a shift key to access? This file maps `1` to be `!` and the
inverse, `Shift+1` to be the actual `1`. It does this for all the numbers.

A close second beind this is invert-programming-keys.txt.

programming-keys.txt
--------------------

As one who programs a good deal of JavaScript code, again in my analysis, I
found I use the cury braces much more than the square brackets. Thus, this
inverts the `[` and `]` keys just as invert-number-row.txt does.

qwerty.txt
----------

My personal base level mapping.

This includes invert-number-row.txt, and programming-keys.txt. In addition:

* Remap the thumb cluster as I have found my right thumb was used much more
  than my left thumb.
	* Left thumb outer is now the space key
	* Left thumb inner is now backspace
	* Right thumb outer is now the enter key
	* Right thumb inner is now the delete key
	* Right thumb `Win` key is now another `Alt` key
	* `Home` and `Page Up` are now `Left Shift` which allows for easier
	  keyboard shortcuts as the `Ctrl`, `Alt` and `Shift` keys are all next to
		each other
* Remap the `International-\` key to be the `Win` key as I took that away on
  the thumb cluster because I needed an `Alt` for the right hand
* Remap `Caps` to be `Right Alt`. The thumb keys both have `Left Alt`. What this
  does is gives me a modifier key that is not used anywhere else. Thus, I can
	create a "fake" additional layer by pressing the `Caps` key and any key on
	the keyboard. Keys have to be programmed as a macro.

**Programming Macros**

* `Caps+Enter` goes to the end of the line, then presses enter. This "opens"
  a line below the cursor.
* `Caps+Shift+Enter` goes up one line, to the end of the line, then presses enter.
  This "opens" a line above the cursor.
* `Caps+Comma` goes to the end of the line, inserts a comma, and then presses enter.
* `Caps+Open Curly Brace` goes to the end of the line, inserts an open curly
  brace, and then presses enter.

1_qwerty.txt
------------

My personal base level mapping plus my inverting keys. I use this when
programming.

colemak.txt
-----------

Based on the Qwerty base layer, this provides the Colemak layout.

https://colemak.com/

norman.txt
----------

Based on the Qwerty base layer, this provides the Norman layout.

https://normanlayout.info/

workman.txt
-----------

Based on the Qwerty base layer, this provides the Workman layout.

http://workmanlayout.org/
