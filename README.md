# SprocketMeshConverter
Version 0.1. Made by Argore

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

After that, choose the type of compartment (hull or turret), where the file should be saved, and what it should be named.

![image](https://user-images.githubusercontent.com/45431685/148393470-a1489bc6-f4ff-4b92-8264-0c4c49b88c8c.png)


### Importing it into Sprocket.

\*note, this will change soon so that the program saves a .blueprint file instead.

You should now have a .txt file. Open it, here i am using [Notepad++](https://notepad-plus-plus.org/). It should look something like this

![image](https://user-images.githubusercontent.com/45431685/148394716-357dd2df-c443-4683-b600-8bd61f56f77e.png)

Now go to `Documents\My Games\Sprocket\Factions\yourFaction\Blueprints\Vehicles` and open the .blueprint file you wish to edit. If you are editing an already existing vehicle, make sure to create a backup.

#### For the hull:

Replace the first compartment and save. Make sure you selected "hull" in SMC for this.

![image](https://user-images.githubusercontent.com/45431685/148395665-9e670eab-0cd9-4d98-8e45-e3760c65152c.png)



#### For the turret:

Paste it after the hull compartment. Make sure you selected "turret" in SMC for this.

![image](https://user-images.githubusercontent.com/45431685/148395810-71adb959-14a2-497d-93e7-25c202cc4490.png)


Now save, and reload the vehicle in Sprocket. You can now adjust the imported model using the in game transform tools.

![image](https://user-images.githubusercontent.com/45431685/148396334-680f778c-8222-49d9-bedd-3e1147424f0a.png)
