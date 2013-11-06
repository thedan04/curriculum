Text Editing 101
****************

Typing 50 WPM
=============

``vi``
======

``vi`` is an extremely powerful text editor which leverages the ``ed`` line editor.  This utility is available on nearly all Linux systems, however many users feel that there is a steep learning curve.  Becoming familiar with it's usage can be very beneficial to learning search and replace syntax for other programs using ``ed`` such as ``sed``.  There are multiple modes to be aware of when using ``vi``:

Command and Insert mode
-----------------------
The command mode is used for actions such as navigating throughout the document or performing search and replace functions.  

To enter ``Insert`` mode hit the ``i`` key.  To leave ``Insert`` mode hit ``esc``.  

Entering commands can be done by first entering ``:`` followed by the command sequence.

Word motions
------------
It is possible to navigate across a line, one word or WORD at a time rather than one character at a time which can greatly increase the speed of navigating to the exact location you are targeting.

Line Numbers
------------
Turn on or off line numbering with:

  :set number

  :set nonumber

Professional Fonts (vim?)
-------------------------

Syntax Highlighting (vim)
-------------------------

Directory navigation (NERDtree)
-------------------------------

Edit/Open/Close Files
---------------------

Edit/Open/Close Buffers (vim)
-----------------------------

Search and Replace
------------------
To replace the word old with the word new, only for the first instance of the word old on each line.
  
  :%s/old/new/
  
To  replace every instance of the word old with the word new in the current document.

  :%s/old/new/g

