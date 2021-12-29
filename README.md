# 3D-TerreiroPaco-Lisbon

A 3D virtual reality scenario of Lisbon's `Terreiro do Paço` with the aim of treating phobias and others
psychological disorders.


https://user-images.githubusercontent.com/78174997/144131087-261ae7dd-e464-4014-b648-3e758453b0ba.mp4


## Introduction

Using virtual reality scenarios to treat phobias and other
psychological disorders is getting more frequent. The project goal is to
model from scratch a 3D virtual scene that could have been used with the purpose of
treating these phobias.

The virtual setting portrayed in this work is an urban setting inspired by Lisbon's `Terreiro do Paço` or `Praça do Comércio`.
To portray this 3D scenario, `Blender` was used as the main tool.

To perform the modeling, Google Earth was used to verify the actual measurements of monuments and buildings.

---

## Technologies

- Blender

---

## Instructions to Execute

- Download this zip [Terreiro do Paço - Lisboa](https://drive.google.com/file/d/1qBDZS8vcQc0IF9ftoRGI25hRdBCtIOGc/view?usp=sharing)
- Extract 
- Open `terreiroPaco.blender`

---

## Requirements

- Blender

---

## More about 3D-TerreiroPaco-Lisbon


![1](https://user-images.githubusercontent.com/78174997/147681421-631dd0fc-cc1c-47bd-aaca-2f27f2213fb8.png)

#

### Introduction

The use of virtual reality scenarios for the treatment of phobias and other 
psychological disorders is increasingly common. The goal of this paper is to
model from scratch a 3D virtual scenario that could have been used for the
treatment of these phobias.

The virtual scenario depicted in this work is an urban scenario inspired by the Praça Do Comércio of the city of Lisbon. To portray this scenario we used the "Blender" tool.

To make the modeling of the Praça do Comércio we based on the model of the Praça do Comércio from Google Earth. And from it we created a plan with the real measures.

The work is divided into two parts:
- Modeling of the desired scenario;
- Animation with images captured with two cameras, one with the aerial view of the scenery and another that simulates the point of view of someone taking a walk in the square.

# 

Figure 1 - Praça do Comércio (Google Earth)

![2](https://user-images.githubusercontent.com/78174997/147681231-9eae1e99-6d66-4cca-a354-5f40f6c6b240.png)

Figure 2 - Praça do Comércio (Google Earth) with measurements

![3](https://user-images.githubusercontent.com/78174997/147681694-c37e599b-832e-4dba-acb9-e674666d11ad.png)

#

## Part 1 - Modeling

We will now explain how to proceed to perform each part of the modeling work in Blender.

### Augusta Street Arch

To make the arc of Augusta Street, first we added two cubes that were placed at a distance of 9 meters from each other.
were placed at a distance of 9 meters from each other, then we made a scale increase on the Y axis to make each cube into a parallelepiped enlarged to a height of 20m and we increased the scale on the x-axis until we reached the measurements of length. So each of these cubes became columns (supports) of the arch.

Then, for each column, we extruded the top face of the column to create the
top ledge of each column. Then we pulled up and created a new
parallelepiped above the column, we extrude faces again but this time on the front face of the same parallelepiped by pulling on the X-axis (in the
direction of the red arrow in the figure above), creating a ledge, over this ledge we select the bottom edge and use the "Chamfer" feature with the "Profile
Type>Cornice Molding " splitting it into several segments to create the effect in Figure above.

To create the arc itself we started by adding a cylinder between the two arcs,
which was rotated 90° to be horizontal, then scaled to a different scale, and
then we changed the scale until the diameter of the cylinder is equal to the distance between the arches, we perform a translation of the cylinder to the top of the columns
until the upper arc of the cylinder is like a bridge over the two columns, then we remove the interior part of the cylinder and all the lower faces, leaving only the faces that served as a "bridge" between the arches, leaving only the faces of the cylinder. Then
on all these faces we apply the Extrude to pull them and give each of these
faces thick. After all this process we place a parallelepiped lying on
columns and above the arch and add another cylinder inside the same parallelepiped and over the arch created inside the parallelelepiped. On this
parallelepiped we applied the function "Add Modifier> Boolean> Difference"
between the parallelepiped and the cylinder that was added thus creating an arc, then
to finish we delete the inner arc that served as the mold and the cylinder that was
added. Then on the edges we once again apply the "Chamfer" with "Profile
Type>Cornice Molding" to give the arch the Manueline style.

To create the column bases we subdivided the left and right columns, and
once again extrude the front face of this lower subdivision, and
applied the "Chamfer" to the upper edge with "Profile Type>Cornice Molding".
For the two front columns we used cylinders with several faces by placing them
on cubes that served as the base.


Figure 3 - Chamfering Function with Cornice Molding

![4](https://user-images.githubusercontent.com/78174997/147682554-c3d50299-a005-4b28-aa28-1b13bf27c2f5.png)

Figure 4 - Arch

![5](https://user-images.githubusercontent.com/78174997/147682626-69aeaf2c-c60e-4de0-bf8b-fe4da9e54075.png)

Figure 5 - Column

![6](https://user-images.githubusercontent.com/78174997/147682701-e70773aa-e842-4a80-b199-05d438d1295b.png)

#

### Central Statue of King José


To model the central statue of King D. Joseph we start at the base of the statue, In
Edit Mode -> Add we introduce a circle of radius 10m, and through a scale
change of scale we turned it into an ellipse to better represent the shape of the base
of the real statue.

We created another circle exactly like it and placed it on the same axis as the X and
Y axis, but the Z axis was slightly enlarged to create a first step.
Next we created the steps that represent the stairs of the statue.
Following the same procedure, we placed successive circles,
progressively increasing the Z axis (position of the object) and applying
constant changes of scale in the upper circles.

To maintain the coherence of the positioning and the height of the stairs' steps,
we were guided by the Euler Mode XYZ, where for each upper stair we increased the
Scale Z by 0.3 and decreased the Scale X and Y by 0.04 in order to create a visual effect of the steps in an upward direction.
After the stairs we modeled the upper base of the statue.
To do this we created another circle, turned it into an ellipse, placed it on the
axis above the stairs and then dragged some vertices to create the squares at each end of the ellipse, to resemble the real statue.

Then we create a column. Object Mode -> Add -> Mesh -> Cube. We took the cube
cube, applied a scale change
to make it longer. We added another cube and applied another
change of scale to flatten it as much as possible to make the detail of the
column.
To make the top of the column we inserted another cube, and using the
Knife tool we cut it in half.
We applied several changes of scale to make it look like the figure 6.

Then for the top we introduced a cylinder and a cone and reduced both
objects. We multiplied that column 16 times putting 4 columns for each square of the
top.
To imitate the statue's bars we added a cube and flattened it in width
to resemble the width of the grid. We did the same for each of the
different dimensions of the grids.

Then we finally built the statue part.
We placed three cubes, one for the middle and two for the sides. We applied
so that the middle cube is 9m wide by 4.5m long, and those on the sides are
long and the ones on the sides are 4.5m wide by 1m long.

To lay the statue of King Joseph we placed a cylinder 5m high and centered it with the rectangle centered it with the rectangle in the middle.
For the statue itself we imported two free models from the internet
a man and a horse and sat them on top of the cylinder.


Figure 6 - Statue Column

![7](https://user-images.githubusercontent.com/78174997/147683466-d85c8fea-188b-4818-a638-d4b65313a824.png)


Figure 7 - Statue Render Image

![8](https://user-images.githubusercontent.com/78174997/147683482-5de3d6e7-b5a7-462d-998c-dc8eb142d8d7.png)

#

### Spheres

We created 5 spheres and put them in the center of
Commerce Square. For their creation we did Add -> Mesh -> UV Sphere.
To replicate the waits we did
just ctrl C ctrlV or else Shift + D.
To make the sphere really round, we clicked
on the sphere and right-click and choose the choose the Smooth Shade option.
Next we choose the materials for the sphere,
first a color in Base Color and then we move
Metallic and Roughness properties to have 5 spheres with different levels of brightness and transparencies (Figure 8)

Figure 8 - Menu for creating the sphere specifications

![9](https://user-images.githubusercontent.com/78174997/147684288-f2a2abff-a0ab-4940-8cee-b0a812f7544c.png)


Figure 9 - View of the spheres

![10](https://user-images.githubusercontent.com/78174997/147684314-7b3331dd-c8d0-43ff-9315-97e386ae04bd.png)

#

### Buildings

We start by creating a column by adding a cube Add -> Mesh -> Cube and
we approximately measure the height of the building's columns.
To make the details in the column (Figure 11) we select the square at the base
of this column and made an E and clicked on Z to raise the column a certain height, then
we select each of the faces around to create the details of the column, selected
each face, E + (X or Y) depends on the direction you want -> select the edge underneath ->
Cntrl B and modify the Bevel settings so that we create these edges. Then
we select a base again in order to increase the height. After the column is done
we duplicate the column. To connect one column to the other we do E until it touches the other one in order to
join them together.

To create the arc we used a cylinder, eliminate the two bases and half of the
faces, then create its bases again. We put this semi-cylinder between the two columns and did Alt+S to create the arc. To complete the remaining space
we put a Cube to occupy the free space between the arc and the two columns.
To replicate all the arcs we took Figure 12 and removed one of the columns, then Ctrl J.
To make the several columns we did Modifier Properties -> Add Modifier -> Array -> Count.
Modifier -> Array -> Count. We set the Count depending on the number of arcs we wanted.

The inner arches of the buildings we use the same ones created in Figure 12.
just make them a little wider by changing the arc. To replicate them we used the same
Modifier Properties -> Add Modifier -> Array -> Count.

Figure 10 - Bow used

![11](https://user-images.githubusercontent.com/78174997/147685075-84adb157-e5a4-40ea-a8bd-dcdcfce03fa1.png)

Figure 11 - Arc Details

![12](https://user-images.githubusercontent.com/78174997/147685085-d41c0d36-95ef-4767-8766-5080bac389d2.png)

Figure 12 - Replication of arcs using an Array

![13](https://user-images.githubusercontent.com/78174997/147685099-97af47fb-1066-4c64-bb14-9e0bc213d314.png)

There are buildings with one floor and others with two or three floors. The floors of the
buildings were made the same way regardless of the number of floors.
We add a cube to create a part of the floor that corresponds to the width
of the arc, Add-> Mesh-> Cube. We measured and metered the height of each floor with a height. To replicate the floor portions along the arches we did
Modifier Properties -> Add Modifier -> Array -> Count.

To create floor 0 of the floors we added a cube Add-> Mesh-> Cube and to
replicate the floor plots along the arches we Modifier Properties -> Add Modifier -> Array -> Count.
To make the facade Add-> Mesh-> Cube and used the modifier Array exemplified already
previously.
The roof was made by 2 planes Add-> Mesh-> Plane. To connect them
we selected the vertices in Edit Mode and joined them with F.

To replicate the roof along the building Modifier Properties -> Add Modifier -> Array -> Count. One part of the roof had to take more detail and mess with the
vertices along the XYZ Cartesian referential.

Figure 13 - View of the modeled buildings

![14](https://user-images.githubusercontent.com/78174997/147685298-1ddde2de-70ce-4797-bbcf-f17fdb3be3b6.png)

There are 2 types of columns in the buildings (Figure 14).
Both were created from Add->Mesh->Cube cubes, to create their
edges we extract the faces by using E and selecting an edge and clicking Ctrl B.
To be more prominent in one area we use Ctrl R to cut out the faces of the
original cube and then E to stick out and make the edge stick out further. The rounded top of one of the columns we added a cylinder Add-> Mesh -> Cylinder
we cut the cylinder in half deleting the 2 faces, removing half the faces and
selected again the vertices in Edit Mode and when selecting the desired vertices
to make a face click F.

Figure 14 - Building columns

![15](https://user-images.githubusercontent.com/78174997/147685452-89b0c92d-e2b2-461d-9346-38707bd4474f.png)


#

### Textures

On all the objects in our work we apply images to the objects in order to create a more real effect. The images were all taken from Google and
worked in order to be as real as possible. To add a texture to an object it is necessary to do the following steps:
- Click on the object and go to Material Properties -> select a New in order to
make a new material (Figures)

- Then go to the menu Shading that is on top in the same line of the Layout
- In the Shading editor choose Add-> Texture -> Image Texture or simply drag the image there.
- Connect the color from the Image Texture menu to the Base Color from the Principled BSDF menu We perform this method on all objects in our project.

Figure 15 - Creating a Texture Material

![16](https://user-images.githubusercontent.com/78174997/147686050-ed29d50e-c4ce-4cb9-a3af-d113566c73e4.png)


Figure 16 - Creating a Material to add Texture

![17](https://user-images.githubusercontent.com/78174997/147686061-12b1ff06-08d6-455a-8e39-ed2f2c34dfc9.png)


Figure 17 - Inserting an Image to Add Texture

![18](https://user-images.githubusercontent.com/78174997/147686071-9d7ea4f0-f03e-4c3e-b8dd-fafb4783b757.png)


To improve the texture and get it right select UV Editing, select the piece to
to put the texture into, enter the Edit Mode, select the face to be moved and adjust the vertices
so that the image looks the way we want it.

Figure 18 - UV Editing Menu

![19](https://user-images.githubusercontent.com/78174997/147686184-50e0dc5e-a66b-4c90-8ddd-858a1d3a36b1.png)

#

### Floor and lamps

The lamps were taken from a free online format and applied to the
work. There are 4 lamps in the center of the Praça do comercio.
The floor of all the buildings and the whole shopping plaza was made with
Planes and we gave texture, Add-> Mesh-> Plane.
There are some that are higher than the others in order to simulate a small step or
level deviation between one floor and another, for this we simply increased the
value of Z since they are all at the same level.
The floor in Figure 20 was made only the parts selected in red and
then applied Modifier Properties -> Add Modifier -> Array -> Count.

Figure 19 - Pavement

![20](https://user-images.githubusercontent.com/78174997/147686534-297d42fc-a29c-47b7-adf5-d1bc3bc2ae2b.png)

Figure 20 - Pavement

![21](https://user-images.githubusercontent.com/78174997/147686539-4fac656b-332e-455d-9a40-07b5c309350e.png)

Figure 21 - Lamp

![22](https://user-images.githubusercontent.com/78174997/147686621-02600cea-e7cb-4c45-8e0a-157ca0be61b2.png)


#

### Sky and Sun

Figure 22 - Sky View

![23](https://user-images.githubusercontent.com/78174997/147686757-afb84c56-9465-4b6b-ad27-d54a2bc852b2.png)

To create the sky, it was necessary to
to install a blender extension.
Through blender itself it is possible to
make a simulation of the sky and we
used this functionality. To
use it we did Edit -> Preferences -> Addons
Addons (Figure 23) and searched for
"Dynamic Sky" and select the option
"Lighting Dynamic Sky" option.
we allow this option to be available
(Figure 24).
Next we went to Create as
can be seen in the Figure and clicked in Create.
Next we select the sky
created (highlighted in red in Figure 26)
We modify our sky by changing the properties in Figure 25 so that we create the
our way. We chose to put in a
blue sky (Sky Color), change the horizon color
Horizon Color with few clouds and
change the Cloud Opacity and Cloud
Density
When creating the sky we can control
the sun and the lighting of our space at the same time.
This option can be seen in the
Sun Value in Figure 25, we choose to set the sun to a value of 1.0.

Figure 23 - Adding the sky feature in blender

![24](https://user-images.githubusercontent.com/78174997/147686768-5e3f61f0-0d30-4351-9d4c-8050f50f5df3.png)

Figure 24 - Creating the sky

![25](https://user-images.githubusercontent.com/78174997/147686781-daf00696-7be2-4624-bc9c-1ac42446653a.png)


Figure 25 - Properties that change the sky

![26](https://user-images.githubusercontent.com/78174997/147687155-3828721c-211b-471e-8717-120f6d97198e.png)


Figure 26 - Creation of the sky

![27](https://user-images.githubusercontent.com/78174997/147687164-3b9ed392-7bed-4dfe-9c57-9a334697011a.png)

#

### River

Figure 27 - View of the Tagus River

![28](https://user-images.githubusercontent.com/78174997/147687279-61032b75-d0ab-4623-9dbe-6f7e9c0f8b6a.png)


For the creation of the Tagus River, we start by adding a square in, Add -> Mesh -> Plane. Next we select our Plane and access the Modifier Properties
and change the functions marked in Figure 28 with a red rectangle, in order to
create our river. In Repeat X and Repeat Y we choose the size of our Plane.
We choose our Resolution and the Scale of the waves.

We select the Foam option that allows us to get and choose the foam of the waves and we give it the name
foam" and choose a Coverage of 0.1
To get the Foam into our river and choose the color of the river we access the
Shading Menu.

We made these connections so that we could
the river effect as can be seen in Figure 28.
Figure 28. To add the following menus
click on Add and choose the desired one. In the
Principled BSDF menu we select the Base Color and
we change the Transmisison to 1
We add the Atributte menu and in the name we give it the same name we had given it when we activated the
Foam option described above.
In the ColorRamp Menu we set the brightness and
darkness of the river.
To make this effect we selected from the river we made
the following connections between menus (Figure 29)

Figure 28 - Properties changed for creating the river

![29](https://user-images.githubusercontent.com/78174997/147687523-2b2b5130-ab37-41f6-9045-8bf023c2be89.png)


Figure 29 - Creating the River - Texture Mode

![30](https://user-images.githubusercontent.com/78174997/147687534-5e243781-4e39-4d9f-b1d1-2bc654f8cff8.png)

#

### Pigeons

The pigeons we got a model of a pigeon online and put some pigeons
along the praça do comercio both on the ground and on top of the buildings and the
the arch of Rua Augusta.

Figure 30 - Pigeons

![31](https://user-images.githubusercontent.com/78174997/147687619-661d4253-529b-4865-95d2-d4d38c54a308.png)

 #
 
 ### Stairway by the river

To model the stairs by the river, we start with Edit Mode -> Add
introduce a circle of radius 70m, and by changing the scale
we make it into an ellipse by flattening the sides.
With the Knife tool we cut the object in half, leaving only half
of the circle.
We created another circle exactly like it and placed it on the same axis as the X and
Y,
axis, but the Z-axis was slightly shortened so as to create a first step in a downward direction.


Figure 31 - Stairway by the river

![32](https://user-images.githubusercontent.com/78174997/147687867-4cdc286c-2114-4eed-bb8d-d2d75cfd712d.png)

To create the other 3 steps, we followed the same process, and to
positioned correctly we were guided by the XYZ Euler Mode, where for each upper stair
Scale Z and Scale X while keeping Scale Y the same.

#

### Buildings

We start by making a facade on one side. We create a parallelepiped
with Add-> Mesh-> Cube, making just one block that corresponds to a window. From
Next we made an array to recreate the various windows on each floor. Columns were created
from a cube. For the different floors we always did the same method described
above. The borders and details were made in the same way as described in
Point of the Buildings.
After that the columns were made from a cylinder.
For the roof we took a cube and removed one of the faces by clicking M->Alt
Center and decreased the height of the pyramid from one of the vertices.
After creating one side of the building we replicated it and rotated it to recreate
the building.
For the blank space between the facades we put a cube to fill and
put it all together.

Figure 32 - Building Facade

![33](https://user-images.githubusercontent.com/78174997/147688013-0fab0a66-4c10-447a-96a4-608bb90b8862.png)

#

### Projections

### Perspective Projection

In a perspective projection the parallel lines parallel to the plane of projection are maintained.
In Figure 33 we see that the blue lines are not parallel to the plane of projection.
Therefore, the blue and green lines are not parallel to the plane of projection,
will not maintain their parallelism. As the user's perspective is an aerial perspective, therefore being above the horizon line, then we can recognize three vanishing points
points, realizing that each one is positioned on its respective horizon line.

Figure 33 - Perspetive Projection

![34](https://user-images.githubusercontent.com/78174997/147688236-7c658813-5d2d-4734-afe0-516185b62e8e.png)


### Parallel Projection

In a parallel projection the plane of projection cannot be parallel to the Direction of
projection.
In Figure 34 we observe an orthogonal parallel projection, because all lines
maintain their parallelisms. We verify this because the projectors are parallel to each other and to the
direction of projection. We drew some lines in the figure below to prove this.


Figure 34 - Parallel Projection

![35](https://user-images.githubusercontent.com/78174997/147688437-4c3aea5b-2b9e-4648-8685-1ef73cc84eea.png)


#

### Shading

In the Flat Shading algorithm, also known as constant or uniform shading
assigns the same color to all pixels belonging to the image of a given polygon, thus
each polygon of an object is colored in its entirety with the same color. The result
clear evidence of polygons, in the transition between adjacent polygons there is a discontinuity corresponding to the normal discontinuity. This discontinuity is easily detectable by our eyes and is even amplified due to the effect of the Mach bands
where there is a difference in coloration between adjacent faces, our eyes tend to exaggerate this difference, at the boundary between two faces, the dark face looks darker and the lighter face appears lighter.
The advantage of this algorithm is the low computation cost and the disadvantage is that
in curved or circular objects, it removes the natural circular effect, making the objects less
realistic due to the ease of detection of these polygons.
To apply this algorithm to the ball, we select the ball in Object Mode
then the right mouse button and then "Flatten Shade".

Figure 35 - Flat Shading Ball

![36](https://user-images.githubusercontent.com/78174997/147688722-877aa85e-8f5f-42d4-abb1-b2f31481eebc.png)


The Gouraud Shading algorithm, also known as Shading with interpolation
intensities, the intensities of the vertices are calculated from the normals at the vertices. At each vertex the average of the normals of the polygons sharing the vertex is taken as the normal to the surface.
of the polygons that share the same vertex. Thus, this algorithm calculates the
color of the pixels on the edges based on the colors of the polygons adjacent to them,
then the color of each pixel is based on the colors of the pixels on the edges. The
problem with this algorithm is that you can lose highligths, the brightness of a bright object
that were expected to be present in the image because this algorithm interpolates colors
because this algorithm interpolates colors from the colors of the vertices. So, when
happens a highligth in the center it will be rendered poorly because the algorithm depends
the vertices, but when there is a highligth in the corner of the polygon there is no longer
this problem.
To apply this algorithm to the ball, we select the ball in Object Mode and click on the
the direct mouse button and select "Smooth Shading".


Figure 36 - Gouraud Shading Ball

![37](https://user-images.githubusercontent.com/78174997/147688897-59e8fc35-ed3a-4b24-a75d-bc50a801253b.png)


#

## Part 2 - Animation

The animation was made using the Follow Path method, which consists of an object
to follow a certain path.
For its realization we created an empty cube
to put the camera inside and follow its path,
Add -> Empty -> Cube, (Figure 37) and create a
Add-> Camera (Figure 37).
Then we clicked on the camera and the empty
Cube and we made the following control Ctrl + P to join
the 2 objects into one Figure.

Figure 37 - Creating the animation

![38png](https://user-images.githubusercontent.com/78174997/147689161-5ed8a43f-d87f-4c12-b82b-731717fead22.png)

To create the camera path we did Add->Curve->Path.
Curve->Path.
We clicked on the Cube and in Object Constraint Modifier-> we added Follow Path->
Target: the line we want it to follow (Figure 38 ). To add path
we right-click on the path in Edit Mode and click on Extrude
Curve and Move or E and make the path our way.
For the camera to move we select the Fixed Position option (Figure 38) and in the
initial position we set the Offset Factor option to 0 and click the button next to this
option, when we want it to end, we set the camera to the frame that we want the
end camera and set it to 1 and click on the ball next to this property to fix the positions in in the animation editor. Then we click on Animate Path.
The bird's eye view animation was made with 3 cameras traversing the Commerce Square,
when we want to tell the duration and frame time that each camera has we do what
what was said in the previous paragraph. The cameras in this mode were recorded at an altitude of about 90 metersof altitude to simulate a drone.
The first-person view animation was done with 5 cameras traversing the Praça do
Comercio Square. This camera simulates the view from a person's perspective.
We used several cameras, 8 cameras in total, and to make their transitions in the Editor
Timeline we clicked on the desired camera and did Marker->Bind Camera to Markers
to select that the camera we want to record at that moment is the main camera
and the one that has the view and is recording at that moment (Figure 39)

Figure 38 - Creating the Animation

![39](https://user-images.githubusercontent.com/78174997/147689780-06742dff-4ad0-49af-a9d9-71bebfce77da.png)


Figure 39 - Creating the Animation

![40](https://user-images.githubusercontent.com/78174997/147689789-cf0c0347-19a9-4039-92a4-c49ace6099fd.png)


Here we show the view of the paths of our cameras. To make the animation
we had to put the end in the editor noddo to end at the final value that we want the
end the animation

Figure 40 - Creating the Animation

![41](https://user-images.githubusercontent.com/78174997/147689937-13417230-8f19-4e13-acb3-e3b3caa3991b.png)


Figure 41 - Frames and recording the animation

![42](https://user-images.githubusercontent.com/78174997/147689947-0999a9c5-ddea-499a-b3aa-927b3d599677.png)


## Material used

- https://www.youtube.com/watch?v=wum312hb8to&list=LL&index=1
- https://www.youtube.com/watch?v=mkD7S7wLx1I&list=LL&index=2&t=219s
- https://www.youtube.com/watch?v=snkXktDTPCM&list=LL&index=3
- https://www.youtube.com/watch?v=-3WbH_VzmG4&list=LL&index=4
- https://www.youtube.com/watch?v=LeYUk3Ob5W8&list=LL&index=5
- https://www.youtube.com/watch?v=HMbWj_KX-4k&list=LL&index=6
- https://www.youtube.com/watch?v=KSZaTEGVowY&list=LL&index=7&t=253s
- https://github.com/ranjian0/building_tool
- https://free3d.com/pt/3d-model/pigeons-in-fence-62670.html
- https://free3d.com/pt/
