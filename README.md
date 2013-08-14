tickler
=======

An [electronic tickler file](http://en.wikipedia.org/wiki/Tickler_file) using Hazel on OSX.  It allows you to file documents and directories away and have them automagically reappear at a pre-defined date in the future.


## Requirements
You need a Mac running OS X 10.6 (Snow Leopard) or higher and a recent version of [Hazel](http://www.noodlesoft.com/hazel.php) - it was created on V3.1.3.  Do yourself a favour, if you're not running Hazel, just go and install it now - it's the best automation tool available on the Mac.



## Installation
* Import the rule `Downloads.hazelrules` into Hazel under the directory you want to use as your **inbox** directory (I use `$USER/Downloads`).  
* Create a tickler directory
* Change the folder that the **Tickler files** rule moves things to to match your tickler directory
* Import the rule `tickle.hazelrules` into Hazel under the directory you want to use as your tickler directory
* Change the folder that the **Move files** rule moves things to so that it matches your **inbox** directory
* **OPTIONAL** install the `Tickler.textexpander` rule into [Textexpander](http://smilesoftware.com/TextExpander/index.html) to make *tagging* files with the date easier
