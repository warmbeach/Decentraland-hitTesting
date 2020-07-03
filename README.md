# Decentraland-hitTesting
Create a model in Blender and then interact with it from a scene in Decentraland

First, we need a model to do testing on.  If you dont already have it, go to https://www.blender.org/download/ and get the latest version of blender.  Its free, its full of features, and it creates the types of files needed in Decentraland.

Open blender and click on New File -> General:
<img src="./ReadMe/blender_1.png">

When the new file opens, a cube will be selected (highlighted with orange around the edges).  Hit the "X" key and confirm that you want to delete the cube:
<img src="./ReadMe/blender_2.png">

Click on Add -> Mesh -> Grid to get a new grid that we can use to create various areas to hit test on:
<img src="./ReadMe/blender_3.png">

Type "S" to scale the plane and move your mouse until the coordinates show that its roughly 3.0000 X 3.0000 X 3.0000 (it does not have to be exact)
<img src="./ReadMe/blender_4.png">

From the Scene Collection, expand the Grid and select the Grid that you just created so the grid will be displayed
<img src="./ReadMe/blender_5.png">

Select the vertices (points) around a 2 X 2 grid in the top corner.  You will need to select the vertice in the center of the collection as well:
<img src="./ReadMe/blender_6.png">

Right-click on the selection you just created and click on Separate -> Selection:
<img src="./ReadMe/blender_7.png">

You will now see that your selection is no longer a part of the original grid, and that it has its own entry in the Scene Collection - `Grid.001`
<img src="./ReadMe/blender_8.png">

Repeat this for the remaining 3 corners of the plane so you have `Grid.001` through `Grid.004` in the Scene Collection
<img src="./ReadMe/blender_9.png">

Now do the same for the center of your large plane with a selection that is 3 X 3
<img src="./ReadMe/blender_10.png">

And sepearate it so it becomes `Grid.005`
<img src="./ReadMe/blender_11.png">

In the scene selection pane of blender, you can now click on the eyeball next to `Grid` and it will turn off visibility for the rest of the plane leaving only your new meshes
<img src="./ReadMe/blender_12.png">

Make sure you are in Edit Mode, and use the Zoom button by clicking and holding down while also moving the mouse/trackpad to zoom out so you will be able to select all of your `Grid.001` to `Grid.005` meshes on the screen
<img src="./ReadMe/blender_13.1.png">

Now Select all the meshes by clicking and dragging a rectangle around them so all the parts of the mesh are inside the rectangle selection area
<img src="./ReadMe/blender_14.png">

Select `Extrude` and Select -> All to select all the visible meshes on the screen
<img src="./ReadMe/blender_15.png">

Grab the plus (+) with your mouse/trackpad and pull it up until your flat meshes turn into cubes
<img src="./ReadMe/blender_16.png">

Now lets give each cube a unique color.  Click on `Grid.001` in the Scene Collection and expand it and select `Grid.001` in the menu and then click the `material properties` and then `New`
<img src="./ReadMe/blender_17.1.png">

Click on the base color, and then choose a color from the color wheel by clicking inside the color wheel.  Choose a shade of red for `Grid.001`
<img src="./ReadMe/blender_18.png">

Once you choose your color from the color wheel, you will see that color has been assigned to your cube, however it will not display on screen in that color while in `Modeling` mode
<img src="./ReadMe/blender_19.1.png">

Choose the `Shading` view from the top menu and you will now see the color red on your cube
<img src="./ReadMe/blender_20.png">

Repeat this process for the remaining 3 corner cubes by going back to `Modeling` view and giving each of the remaining corner cubes a unique color.  Check your work by going back to `Shading` view and make sure all the cubes are a different color now
<img src="./ReadMe/blender_21.png">
