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


### Introduction

The use of virtual reality scenarios for the treatment of phobias and other 
psychological disorders is increasingly common. The goal of this paper is to
model from scratch a 3D virtual scenario that could have been used for the
treatment of these phobias.

The virtual scenario depicted in this work is an urban scenario inspired by the Praça Do Comércio of the city of Lisbon. To portray this scenario we used the "Blender" tool.

To make the modeling of the Praça do Comércio we based on the model of the Praça do Comércio from Google Earth. And from it we created a plan with the real measures.

The work is divided into two parts:
- Modeling of the desired scenario;
- Animation with images captured with two cameras, one with the aerial view of the scenery and another that simulates the point of view of someone taking a a walk in the square.

Figure 1 - Praça do Comércio (Google Earth)

![2](https://user-images.githubusercontent.com/78174997/147681231-9eae1e99-6d66-4cca-a354-5f40f6c6b240.png)

Figure 2 - Praça do Comércio (Google Earth) with measurements

![3](https://user-images.githubusercontent.com/78174997/147681694-c37e599b-832e-4dba-acb9-e674666d11ad.png)


### Part 1 - Modeling

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


