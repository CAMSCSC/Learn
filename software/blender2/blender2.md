#Blender 2
## Creating a Humanoid
![](start.PNG "Fig. 1 The Start Screen")

Press '1' then '5'

![](15.PNG "Fig. 2 Front Ortho View")

Press Tab

![](edit1.PNG "Fig. 3 The Edit Screen")

Press 'A'

![](desel.PNG "Fig. 4 Cube in Edit Mode")

Subdivide the cube

![](subdivide.PNG "Fig. 5 Subdivided cube")

Select half the cube and remove vertices (Toggle "Limit Selection to Visible")

![](half.PNG "Fig. 6 Half of a cube")

Go to modifiers and select the mirror modifier

![](mirror.PNG "Fig. 7 A mirrored cube")

Create the arms by selecting the two top points and extruding

![](extrudearms.PNG "Fig. 8 Extruded arms")

Scale down on the z axis and extrude to add hands and scale up on the z axis

![](scalezaddhands.PNG "Fig. 9 The Torso")

Add legs by extruding. Move the legs apart and extrude to add lower legs

![](AddLegs.PNG "Fig. 10 Headless body")

Rotate the camera to get a side view, select all, scale on the y axis by .5

![](scaley.PNG "Fig. 11 Slimmer body")

Shift + A and add a UV Sphere and place it as a head

![](shiftauvsphere.PNG "Fig. 12 A human-oid")

Add a subdivision surface and smooth out the object with views

![](subsurface.PNG "Fig. 13 The Smoothness")

Press Tab and apply the modifiers

![](ApplyObjectMode.PNG "Fig. 14 The Completed Humanoid")

## Animation

![](xray.PNG "Fig. 15 X-Rayed Humanoid")

Use Z to X-Ray the Model, then use Shift-A to add "Armature -> Single Bone"

![](Armature.PNG "Fig. 16 Adding an Armature")

Press Tab to edit the armature

![](editarmature.PNG "Fig. 17 A Single Bone in Edit Mode")

Select the top and extrude another bone. Continue with the entire body and approximate bones

![](createrough.PNG "Fig. 18 A rough mock-up of bones in the a humanoid")

Tab to object mode and parent the Bones to the Body and hit Ctrl-P and Select Bones -> Automatic Weights

![](objecttoparent.PNG "Fig. 19")



























