---
title: Programmming
layout: home
nav_order: 2
parent: Computer Things
---


# **Programming**


## **Hubris**

“It’s too complicated and probably won’t be used.” Wise and probably true feedback. Wise and probably true feedback I’ve chosen to ignore. 

A program, simply, is a series of commands written and stored into a file, which are then executed when the computer is instructed to RUN the file. 

Why, though? In a setting with both hacking and Warez, why have a programming system? It’s simple really: 



1. Shut up. 
2. It sounded fun - A primary reason I do most things. 
3. Programs don’t require Processing Dice - They’re significantly weaker than Warez, but once executed they don’t require additional resources. 
4. Programs don’t require attention - They’re not as adaptive as hacking, but once executed the user can walk away without continued need for input. 
5. Gives the players an additional chance to do something unexpected - See point 2. Sorry about point 1. 

Writing a program takes anywhere from a few hours to a few days, including the testing and debugging. 

Anyone with a computer and enough time on their hands can code a program, though Console Jockeys are just better at it. 

When writing a program you, the player, will actually need to sit down and write out the program’s instructions (seen below) and hand a copy over to GM for approval or suggestions for possible altering. You then have a discussion with the GM over how long generation of the code will take - probably one command line per hour. 


## **Executing**

A program must be on a device in order to be executed on it, meaning if you want to run a program on a device you’ve just hacked, you’re going to need to Upload it first. 

If executing a program on your own device, it functions without issue. 

If executing on a foreign device, you’ll need to roll (d20) to see if the computer understands the program. There is a 70% (14) chance the program of a non-Console Jockey will operate. For Console Jockey’s the odds improve by 5% (+1) for every template taken. 

Should a 20 be rolled, then the computer crashes trying to figure out the code. 

On a simple failure, however, the program just doesn’t run. 


## **ABASIC**

You won’t be using just any old programming language for all this, instead you’ll be using the most modern and versatile language available to modern man: ABASIC (Advanced BASIC). Well, a severe abstraction thereof. The following is a list of commands available to you. Defining new commands is possible, however you’ll need to write a supporting program for it, as well as fist fight the General Manager (or ask nicely). 

**ACCESS &lt;directory>** - Moves the computer into the specified directory, to continue working. 

**BREAK** - A command for interrupting whatever the system is doing. 

**CLS** - A command that clears the screen of the terminal. Useless for our games of pretend, but it exists. If you want it. 

**CONNECT &lt;address>** - Connects to the remote terminal at the designated address, which is most likely now waiting for an account and password. 

**COPY FROM &lt;source> TO &lt;target>** - Copies a file from source location/account to target location/account. 

**DELETE FILE** - Erases the specified file. 

**DIM** - Declares a variable.

**DISCONNECT** - Opposite of CONNECT. Immediately severs the connection to the remote terminal. Any logged in account remains logged in and unusable until logged off. 

**ELSE** - Paired with IF…THEN. If the condition for the IF…THEN is not met, then this code executes. Must be ended with ENDIF 

**ELSEIF** - Paired with IF…THEN. If the condition of the first IF…THEN is not met, then checks for another condition to execute other code. Must be ended with ENDIF. 

**END** - The last command of a program. Tells the computer to stop what it is doing and without it, the computer will sit and wait forever for more commands. 

**ENDIF** - Informs the computer that the IF block structure is over. 

**FUNCTION** - Defines the start of a function, in case you want to get crafty with your programming. 

**GOTO &lt;line number>** - Moves the computer’s attention to the designated line number. 

**IF…THEN** - The command following THEN is executed if and only if the condition in IF is met. Otherwise the computer ignores the section. Can be combined with ELSEIF…THEN and ELSE to form block structures that must end with ENDIF

**INPUT** - Accepts data input from either a terminal or specified file. 

**LIST** - Lists the contents of the current account or folder. 

**LOAD** - Loads data from the computer for use by the program. 

**LOGON &lt;account>** - Inputs the account name to a remote terminal. 

**LOGOFF** - Opposite of LOGON. Logs out of the current account.  

**LOOP &lt;condition>** - A loop command that causes the computer to repeat a set of commands until the defined condition is met. Loops must end with a NEXT command, or else the computer will only run the loop once and move on. 

**NEXT** - Designates the end of a loop. It tells the system to increment its counter and return to the top of the loop in order to repeat the process. 

**PASSWORD &lt;password>** - Inputs the account’s password to a remote terminal. 

**PATH ///** - Moves a specified file along the defined path. Mostly used in an attempt to confuse any monitoring entities. 

**PRINT &lt;string>** - Prints the defined string to the display. 

**REM** - Designates a remark or note in the code. Not interpreted by the computer, but it makes it easier for humans to read. In case you forget what a section of code is doing. 

**RUN &lt;program>** - Runs the specified program. 

**SAVE &lt;location>** - Stores the currently loaded data onto the local drive as a file with the designated filename and location. 

**SEARCH &lt;query>** - Queries a file or database for data related to the defined query.  

**SLEEP** - Causes the program to pause, waiting until the user presses a key. 

**SORT &lt;condition>** - Used to sort the contents of a file or database by the specified condition. 

**TRACE** - Used to determine the path back to the terminal where the program originated. 

**UNTIL &lt;condition>** -  A loop command that causes the computer to repeat a set of commands until the defined condition is met. UNTIL loops execute until its conditions have been met. Loops must end with a NEXT command, or else the computer will only run the loop once and move on.

**WAIT &lt;time>** - Causes the system to wait for the designated time before continuing. 

**WRITE &lt;destination> &lt;message>** - Writes the message to the destination location. Should no destination be specified, the command defaults to the console. 


### **Comparisons**

Used in conditions to determine if a specified instance is true. Technically not needed for what we're doing, but it looks cooler. 

=	equal to

is	equal to

&lt;>	not equal to

!=	not equal to

>	greater than

&lt;	lesser than

>=	greater than or equal to

&lt;=	lesser than or equal to

**Examples**

Waits three hours, connects to a remote computer, enters account log on data, then loads the data to local and saves, before deleting the remote version and logging out. 


```
WAIT 3 HOURS
CONNECT 126.02.1475.6512
LOGON admin
PASSWORD PetiteConnard69420
LOAD ./McGuffinFile.txt
SAVE TO D:/Home/StolenFiles/McGuffinFile.txt
DELETE FILE ./McGuffinFile.txt
LOGOFF
DISCONNECT
```


IF…THEN example to show what a block structure looks like. 


```
IF var = 1 THEN PRINT "Example 1"
ELSEIF var = 2 THEN PRINT "Example 2"
ELSE DELETE FILE *.*
ENDIF
