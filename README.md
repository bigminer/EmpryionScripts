# EmpryionScripts
This repo is a collection of scripts and my attempt to learn how to use them.

The original authors repo can be found here.
https://github.com/GitHub-TC/EmpyrionScripting

Much of this is not english so I found it hard to understand. 


So far what I have learned.

Every piece of script code is wrapped in curly brackets like this - {{ scriptcode }} 

if you place !-- immediatly after the first two brackets it is a script comment. example. {{!-- this is a comment --}}

set is a keyword that designates a variable followed by 'variablename' and 'value(s)'. So a variable called var would be  ~set 'var' ''
to give a variable a value or list, then do ~set 'var' 'myvalue' or for a list '1,2,3', basically an array

As a convention, to avoid possible conflicts of items in game, use this pattern when renaming items such as containers. ItemName-PlayerInitials-ShipName-somenumber

Container-GM-myship-1 in this example would be  container on my ship

Sanity Checks - Make sure that whatever ship or base you are working with has power or your LCD that run your script will display and do nothing.
 - move your lcd into a group so you can rename it 

CAUTION - changing object names in the game may break existing scripts especially if that item is referenced by several scripts

NOTE - It may take a few seconds before a script appears to do anything

Tip - while looking at an item hit the letter P and open the devices tab. This will take you to the exact item you are looking at. Very useful when trying to figure out what script and objects you are trying to interact with.

Tip - set a code on a script LCD and set to private should help accidental modifications

Tip - consider adding a switch to disable the LCD that contains your script to mimimize overhead on the server. 
      Flip the switch on whenever you want the script to run.