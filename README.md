# Console Killer

Found this script in the wild to prevent people from using Developer Tools on a web site and it's a nasty piece of work. 

It uses:

* A `debugger` statement lock the user into the script debugger 
* Clearing the console every 100 milliseconds to prevent entry
* Blocks context menu and all the different ways to open devtools on load

However, there are ways around :) 


