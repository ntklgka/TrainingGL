# TrainingGL

Part 1: Getting Started

![alt text](https://i.imgur.com/PxElU9F.png)

We can freely move through this scene with FPS-style camera.

Part 2: Lighting

![alt text](https://i.imgur.com/uxz6Vvz.png)

We set up a small white cube which acts as a light source. On the shader code for the big cube, we have implemented the Blinn-Phong Reflection model.

![alt text](https://i.imgur.com/yrsgdex.png)

Implemented diffuse and specular maps, which greatly helps with simulating how light affects different material properties of an object.

![alt text](https://i.imgur.com/LAuiCbS.png)

Attenuation, the light doesnt have a constant intensity anymore. Objects on the back will receive less light.

![alt text](https://i.imgur.com/18ssyaB.png)

Spotlight, simulated a flashlight emanating from the camera position.