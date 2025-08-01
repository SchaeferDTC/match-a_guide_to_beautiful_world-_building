#  Creating a new Gazebo world - 
# or creating new objects and adding them to an existing Gazebo world

![Example world](./images/preview.png) <!-- cool picture of a fancy gazebo world -->

##  Workflow

1.  Create a .obj in Inventor for precise meassurements and simple coloring
2.  Import the .obj file in Blender you may add textures ( .png)
3.  Export from blender into .dae 
4.  Create a Gazebo world 
5.  Add the object 

##  Inventor
Create object,
Use mm.
Export as .obj. This format supports colors. You can either use Inventors materials and colors or just use diffrent colors for diffrent texture groups to replace later on in Blender with the final texture.

##  Blender

#### Step 0 - Switch Blender to mm as defaul unit 
     click on Scene, open the Units tab and change Length from meters to milimeters 
     click on File-> Defaults and save as the new startup file 
#### Step 1 - Import the CAD-Modell from Inventor
     File -> Import .obj
#### Step 2 - Textures and Colors
     Click on UV Editing, Blender should switch to splitscreen.
     In the top left corner of the right screen select edit mode and face select.
     The default mash is mad of triangles, but quads tend to be more useable.
     Select 2 or more triangles and group them up to a quad with the hotkey ALT + J .
     Select all faces and press U and select the smart wrapping option. This proved to be the least distored option.
#### Step 3 - Opening the Texture.png
     Left half, top middle, Click open and select your image
#### Step 4 - Arange your unwrapped mesh 
     Use the Move and Rotate options, Hotkey "3" lets you select Faces, "2" switches to edges and "1" lets you select vortexes.
     Arange the unwrapped mesh. Good luck, you will need it.
#### Step 5 - Use the picture as a material color
     In the option bar to the right select material
     Click on the yellow dot next to Base Color and Press "I" for Immage Texture.
     Now Click on the Picture symbol and select youre used Texture.
     On a good day Blender wont crash.
     To Update the Preview select a diffrent shading option in the top right corner.  
### Last Step - Export as .daae
     File -> Export .dae (legacy)

https://www.youtube.com/watch?v=1YCzHmPI7dM
decent tutorial
