# UPBGE-Spring_Bones
Blender addon to add spring/bouncy dynamic effect to bones.
made by @artellblender and modified by me to add game engine support


## Installation

- Download and install the spring_bones.py file in UPBGE 0.3 or higher
- In Pose Mode, go to the "Spring Bones" panel in the Bone tools section on the right.
- Click "Enable Bone" to enable spring on a bone (must be a child bone)
- You can adjust the "Bouncy", "Speed" and other parameters parameters such as collision
- Click "Start" to enable the effect interactively, or "Start - Animation Mode" to enable it on frame change only (support baking)
- When moving the parent bone, the child will move dynamically with bouncy motion
- To bake, use the Blender baking tool: press F3 > type "bake" > NLA Bake
- To use in game engine select the armature in the "Spring Bones" panel in the scene properties tab
- If you want to run spring bones only in an interval of x frames you can also set this in the scene properties
