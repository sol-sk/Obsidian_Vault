Robot moves x,z: dirToGo
Rotate around y axis
Max speed exists

Raycast
RayPerceptionSensor3D is built in Unity, gets added directly to network observation
Observe any accesible variable
	Sensor.AddObservation acts as inputs to network
Laser 
- setLaser
- Distance is automatic
- Cant move and shoot at same time
- Shots in direction you are facing: transform.forward
- While shooting you cannot move
- Freezes enemy for 3 seconds, 1 second invincible after

Only change the code in the YourGroupName.cs 
Put everything you need inside it
Don't change movement in fixedUpdate 
If it feels like cheating it probably is, can ask on PIazza

Training: how we will reward

Heuristic
- Keyboard input
OnActionReceived
- Action
Moveplayer
- Conditions

