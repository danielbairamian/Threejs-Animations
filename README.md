## Threejs Animations
Set of animations done during my summer 2017 Summer Undergraduate Research in Engineering (S.U.R.E) internship at McGill with professor Derek Nowrouzezahrai

# Basic shapes

First ever threejs program, the goal was to explore the API and get to know it. Goal was to recreate the shape of a dog using basic shapes, include light/shadow, and have some sort of GUI controls to change the parameters (done with dat.gui)

# Deformable body animation

Animation of a cloth by using a particle system that connect a rectangular mesh. The particles are subject to 3 forces: gravity (constant) , wind (Time dependent) , spring (n-ary). The spring structure is composed of Stretch (horizontal / vertical) and Shear ( diagonal ) springs.
Shaders were also used in this animation. 

# Heartbeat

Unlike the other animations, this one has not been done with Threejs, instead it uses basic HTML canvas. The heartbeat animation is achieved by using a variant of the standard cardioid function.

# Rigid body hand animation

Recreation of a hand using basic shapes, and threejs bones that tie the mesh to virtual bones, in order to animate the mesh.

# Soft body hand animation

Step up from the Rigid body hand animation, where the hand now is an actual 3D mesh , the bone structure has been created with the help of Blender. Once exported to threejs using the custom blender to threejs converter, the animation is the same as for the rigid hand.

# Space game

Simple space game where the user is a planet going through meteors. The user's score increases when he/she collects the colored ball. If a collision with a meteor happens, the score is reset to 0. The higher the score, the faster the meteors become.
