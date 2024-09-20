# TopDownRPG
This project is based on YouTube tutorial named AlexQuevillonEn.

The game contains on day 20.09.2024:
- Debug Menu: Most common Commands usable during playing to help debug things as first Tab. It is made with Widgets: Buttons, Overlay, Border, Vertical/Horizontal Boxes, Editable Text, Expandable Area, Widget Switcher etc. DebugMenu containing a lot of utilities to debug things live - setting grid, changing camera, changing environment, changing type of grid, diagonal neighbours, adding units, casting spells, setting AI and so on.
![alt text](https://raw.githubusercontent.com/jakkwi/Games/refs/heads/main/TopDownRPG/Screenshots/debug_menu_console.png?raw=true)

- Camera Control: Zoom In and Out with Mouse Wheel, Rotation by +/- 45 degree on Q/E buttons, Movement with WASD and Arrows. Added Clamp for boundaries and Interpolation to smooth the movement of camera.
![alt text](https://raw.githubusercontent.com/jakkwi/Games/refs/heads/main/TopDownRPG/Screenshots/camera.png?raw=true)

- Grid: Gird depends on environment (trace channel from Z:1000 to Z:0 to catch things that can be tiled), so it's easy to add or remove something on map and the grid will automaticly catch those changes and adapt. There are three types of working grid to use: Hexagon (like Civ games), Squares (Like XCOM), and Triangles (don't know the example for this one). Tiles have types like (flying only or double movement cost, walkable or not and so on). Grid has tactical mode which can disable environment and make game more clear for playing.
![alt text](https://raw.githubusercontent.com/jakkwi/Games/refs/heads/main/TopDownRPG/Screenshots/grid.png?raw=true)
  
- Pathfinding with diagonal and without diagonals. On debug menu we can see indexes, types, cost, sort, discovered, and alaysed list of tiles.
![alt text](https://raw.githubusercontent.com/jakkwi/Games/refs/heads/main/TopDownRPG/Screenshots/pathfinding.png?raw=true)

- Spells: Units (and debug menu) can cast spells with or without line of sight. Single target and/or area of effect. Linetraces, range, shape of spell, and LoS can be modified during game.
![alt text](https://raw.githubusercontent.com/jakkwi/Games/refs/heads/main/TopDownRPG/Screenshots/spells.png?raw=true)

- Combat and AI: Units can move and cast a spell to heal/damage the other units. Teams so we can play with friends vs other teams. Simple AI to walk to/from enemy/ally. Spells tooltip and some basic UI.

<video src='https://github.com/jakkwi/Games/blob/main/TopDownRPG/Screenshots/ai%20combat%20less%20than%2010mb.mp4' />

