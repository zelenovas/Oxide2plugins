Plugin allow admins to create rectangle areas (by coordinates of diagonally opposite corners) with alert (notification) messages.

Available commands
-------------------

**/alertareas help** - show available command.  
**/alertareas list** - show all areas with alert.  
**/alertareas add \<AreaName\> [true]** - add new area (with optional "true" alert text will be shown constantly).  
**/alertareas remove \<AreaName\>** - remove area (case insensitive).  
**/alertareas edit \<AreaName\>** - edit mode where you can set alert text, corners coordinates and 'constant' attribute.  

Commands in edit mode
----------------------

**/alertareas corner 1** - set first corner coordinates.  
**/alertareas corner 2** - set second corner coordinates.  
**/alertareas name \<NewAreaName\>** - change area name.  
**/alertareas text \<Some alert text!\>** - set area alert text.  
**/alertareas constant \<true|false\>** - show alert constantly or not.  

How to create area with notification?
----------------------

1. First of all you must be an admin. If so, type command in chat:  
**/alertareas add AreaNameWithoutSpaces**
2. Once it is added use command:  
**/alertareas edit AreaNameWithoutSpaces**
3. Now you can specify notification text with command:  
**/alertareas text Any notification text!**
4. After that you should stand on the first corner of area and type next command:  
**/alertareas corner 1**
5. Next, stand on the diagonally opposite corner and type command:  
**/alertareas corner 2**
