# TopDownRPG
This project is based on YouTube tutorial named AlexQuevillonEn.

The game contains on day 20.09.2024:
- Debug Menu: Most common Commands usable during playing to help debug things as first Tab. It is made with Widgets: Buttons, Overlay, Border, Vertical/Horizontal Boxes, Editable Text, Expandable Area, Widget Switcher etc. DebugMenu containing a lot of utilities to debug things live - setting grid, changing camera, changing environment, changing type of grid, diagonal neighbours, adding units, casting spells, setting AI and so on.


- Camera Control: Zoom In and Out with Mouse Wheel, Rotation by +/- 45 degree on Q/E buttons, Movement with WASD and Arrows. Added Clamp for boundaries and Interpolation to smooth the movement of camera.


- Grid: Gird depends on environment (trace channel from Z:1000 to Z:0 to catch things that can be tiled), so it's easy to add or remove something on map and the grid will automaticly catch those changes and adapt. There are three types of working grid to use: Hexagon (like Civ games), Squares (Like XCOM), and Triangles (don't know the example for this one). Tiles have types like (flying only or double movement cost, walkable or not and so on). Grid has tactical mode which can disable environment and make game more clear for playing.

  
