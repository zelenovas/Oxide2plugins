Plugin allow admins to create rectangle areas (by coordinates of diagonally opposite corners) with alert (notification) messages.

Available commands
-------------------

**/alertareas help** - show available command.  
**/alertareas list** - show all areas with alert.  
**/alertareas add \<AreaName\> [true]** - add new area (with optional "true" alert text will be shown constantly).  
**/alertareas remove** <AreaName> - remove area (case insensitive).  
**/alertareas edit** <AreaName> - edit mode where you can set alert text, corners coordinates and 'constant' attribute.  

Commands in edit mode
----------------------

**/alertareas corner 1** - set first corner coordinates.  
**/alertareas corner 2** - set second corner coordinates.  
**/alertareas name <NewAreaName>** - change area name.  
**/alertareas text <Some alert text!>** - set area alert text.  
**/alertareas constant <true|false>** - show alert constantly or not.  
