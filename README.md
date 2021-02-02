# Art Pipeline Project
use this to prepare art assets for game implimentation

# 1
Add FBX and Base Texture Maps to "Assets/ART"

# 2
Create a new material using the following shader: "Shader Graphs/Toon"
An example can be seen in the art folder

# 3
Add the material to the FBX and add the base map to the mateial

# 4
Add the model to the scene by dragging it onto the turntable in the scene hierachy (left side)
ensure it is a child object in order to rotate it on runtime
any changes made on runtime will be discarded when you stop running it

# 5
Change the parameters in the material
-shadow size changes the ammount of shadow present
-shadow blend smooths the edge of the shadow
-shadow colour should be left on default unless it NEEDS to be changed
-edge light size and blend affect the cell shading effect
-the posterize colour channels dictate the number of steps to include in the posterize filter

# 6
Once ready you should place the FBX, materials and texture maps in a folder
right click and export it as a package. This can then be easily sent via discord or uploaded to the shared folder
