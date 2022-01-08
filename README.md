# SprocketMeshConverter
Version 0.2.2. Made by Argore

![image](https://user-images.githubusercontent.com/45431685/148399805-2b594068-9b18-4a44-955d-ec228bb59331.png)


## About
This program converts wavefront (\*.obj) meshes into [Sprocket](https://store.steampowered.com/app/1674170/Sprocket/) compartments. It is only compatible with version 0.113 and above.



## How to use
### The mesh.
First step is to get the mesh compatible with SMC and Sprocket.

Here i will be using [Blender](https://www.blender.org/) to prepare the model.

![image](https://user-images.githubusercontent.com/45431685/148389794-619e26f6-564d-4dd8-9222-e33ba31578a0.png)


Make sure it is one object. You can merge objects by selecting them and pressing Ctrl + J.

![image](https://user-images.githubusercontent.com/45431685/148390903-1b2d5a40-3105-4f13-9f92-e93a05ec2c65.png)


Secondly, make sure the mesh is triangulated. Meaning it is made out of triangles and not other shapes.

To do this using blender, select the object and open Modifier Properties.

![image](https://user-images.githubusercontent.com/45431685/148391323-cf32cf7c-4bdd-48d2-aa0f-38b826851169.png)


Add "Triangulate".

![image](https://user-images.githubusercontent.com/45431685/148391368-b017ef62-d8fa-454e-a074-f59748a45879.png)


And apply.

![image](https://user-images.githubusercontent.com/45431685/148391483-a15ed1c5-2e75-4887-9228-e901eb038baf.png)


The mesh should now look something like this

![image](https://user-images.githubusercontent.com/45431685/148391556-87c34171-8670-4d07-8b31-919602a721f4.png)


After this. Export the model as a wavefront (\*.obj).

![image](https://user-images.githubusercontent.com/45431685/148391831-b75d4a88-5161-4318-aef8-7741455668d9.png)


### Using SMC.

Next step is importing the model into SMC.

Open the program and type in the location of the model you exported in the last step, and press enter.

If the last step was done correctly, you should see something like this.

![image](https://user-images.githubusercontent.com/45431685/148393142-8cd2b615-561a-461c-ae4d-4d111f40cafa.png)

Now simply choose your settings:
- Smoothness (smooth/sharp). Whether or not to have smooth or sharp edges. Smooth is good for organic and round shapes, but might cause visual glitches. Sharp is good for hard edges, mechanical stuff, but might be slightly laggier.
- Type (hull/turret). What type of compartment you are making.
- Faction. What Faction you want to save it in. If you're unsure, skip this.
- File name. What you want the compartment to be called.

The compartment should now be saved.

### Loading the model in Sprocket.

Go into Sprocket and open the Base tab.

![image](https://user-images.githubusercontent.com/45431685/148625932-845dc647-1283-475d-b08a-6ebc8c2831d7.png)


If you are making a hull. Press the load compartment button and click on your file.

If you are making a turret. First place down a turret, righ click it. Then load the compartment.

![image](https://user-images.githubusercontent.com/45431685/148626024-4616ed91-448b-458f-9923-c3e736e4cf2f.png)
![image](https://user-images.githubusercontent.com/45431685/148626034-b439eaf9-9e86-4097-92f3-4eb6a2faa4b4.png)


You can now adjust the imported model using the in game transform tools.

![image](https://user-images.githubusercontent.com/45431685/148457152-7d68a133-672f-409b-8afb-bffae7412250.png)
