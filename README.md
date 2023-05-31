# EXNO-04-Attach-Rifle-with-character-mesh
#### PAVITHRA G
#### 212221240036
## Aim:
### To Attach Rifle with character mesh and implementation bullet spawn from Rifle
## Algorithm:
### Step-1: Import the character mesh that you chose and the suitable gun mesh.Ensure all the files are imported correctly.
### Step 2: Create action events to trigger them by pressing the respective key.
![image](https://github.com/gpavithra673/EXNO-04-Attach-Rifle-with-character-mesh/assets/93427264/43a15eda-b987-4c02-b24b-40a58d57de5d)
### Step-3: Open the SKELETAL MESH of the imported character and direct yourself to the skeleton tree. Here we have to create socket at the spinal and in right hand part of the skeleton tree.
### Step-4:Attach the rifle model to the character's attachment point using the appropriate parenting or socketing mechanism provided by your game engine. This will ensure that the rifle follows the character's movements and animations correctly.
![image](https://github.com/gpavithra673/EXNO-04-Attach-Rifle-with-character-mesh/assets/93427264/66a909c7-31d8-4dd6-b078-85363909f383)
### Step-5:After this we have to create a bullet actor, gunactor and specify the direction of the bullet to launch. In event graph make required connection so that the bullet launches correctly. 
### Step-6: In event graph create connection for the gun spawn so that when we click the triggering key and the gun gets spawned to hand.
![image](https://github.com/gpavithra673/EXNO-04-Attach-Rifle-with-character-mesh/assets/93427264/15c2cbd1-afdb-4043-8c9f-5bc3c5bb4bb2)
### Step-7: Now create an event to trigger bullet fire and make appropriate connections so that when key is pressed, the bullet launches. Correct the initial and final velocity of the bullet before compiling.
![image](https://github.com/gpavithra673/EXNO-04-Attach-Rifle-with-character-mesh/assets/93427264/e74d240f-a1a4-4181-a785-c172b757c3e6)
### Step-8: Adjust the velocity of the bullet in ullet actor and make sure all the connections are correctly made.
### Step-9: Additionally make sure that when the gun is spawned to spinalcord the bullet fire option should be disabled.

## OUTPUT:

### GUN ATTACHED TO CHARACTER:
![Screenshot (49)](https://github.com/gpavithra673/EXNO-04-Attach-Rifle-with-character-mesh/assets/93427264/1b0e1900-fe2a-40d4-8ef3-b835f03a9b6d)

### GUN EQUIP:
![Screenshot (50)](https://github.com/gpavithra673/EXNO-04-Attach-Rifle-with-character-mesh/assets/93427264/b19e55d9-e376-4d58-a5e7-d632c9e9ada4)

### BULLTE FIRE:
![Screenshot (51)](https://github.com/gpavithra673/EXNO-04-Attach-Rifle-with-character-mesh/assets/93427264/9108894e-7bc2-4fa0-9f85-18a9e943ad78)

## Result:
### By following the above mentiioned steps we can successfully attach the riffle to the character and fire the bullet when triggering their respective buttons.
