Using Interface with defaultScript.js running …

# Calibration

Hold your arms out to either side in a “T” pose and press the two bumper buttons.

# Cursors

Each controller has its own cursor, drawn as a cyan dot-plus-circle. These act like a normal mouse cursor. You move them by adjusting the pitch and yaw of your controllers.
* **Bumper button:** Left-click.
* **Trigger:** Right-click.

**Developer > Hands > Sixense > Enable Sixense Mouse Input:** Enable/disable the controller cursors.
**Preferences > Invert Mouse Buttons:** Swaps the left- and right-clicks.
**Preferences > Reticle Movement Speed:** Adjusts the sensitivity of the cursor movement.

Your right-hand controller can also control the normal mouse pointer: enable/disable this control by pressing button 0 on the right-hand controller (the small skinny one between buttons 1 and 2).

# Controller Graphics

**Developer > Show Hand Info:** Draws a red disc plus sphere and pointer that depicts your controller orientation. These coincide with your “palm” positions if you have Preferences > Avatar Scale = 1.0; if you don’t then the are drawn some distance away. Note also that your avatar’s hands will not necessarily line up the “palm” positions.

**Developer > Show Hand Targets:** Draws a wire mesh ball the position of your “finger tips”, if Show Hand Info is enabled. These are 0.3m away from your “palm” position.

**Developer > Avatar > Show Skeleton Collision Shapes:** If your avatar scale != 1.0 then you’ll see green balls drawn at your avatar’s “palm” positions.

**Developer > Hands > Sixense > Enable Sixense UI Lasers:** Shows/hides cyan “lasers” emanating from the position of the red disc-plus-sphere-and-pointer.


# Movement

**Left joystick:** Moves you forwards/backwards in the direction you’re looking, and left/right.
**Right joystick:** Rotates your view up/down and left/right.

**Button 4 on either controller:** Press and hold then:
* Tilt and horizontally rotate your controller to tilt and rotate your view.
* Move your controller backwards/forwards/left/right/up/down to move in that direction.
A pair of spheres are drawn to depict your controller’s orientation and movement.

# Voxel Editing

If you have the controller cursors enabled, you can use the bumpers and triggers to delete, add, and extrude voxels the same as with a mouse. (Turn voxel editing on/off with left-hand toolbar’s cube to enable/disable.)

# Model Editing

When you enable model editing (right-hand toolbar’s cube) a pair of lasers is drawn.

**Left- or right-bumper:** Toggle lasers red/blue.
* Red: Mode 0
* Blue: Mode 1

**Single-laser editing:** Make one of your lasers intersect with a model then “grab” it by pulling and holding the relevant controller’s trigger.
* Mode 0: The model rotates around your controller’s location, keeping the model “looking at” the controller, and changing position with changes in your controller’s position.
* Mode 1: The model rotates about its axis as you rotate your controller, and moves position as a multiple of changes in your controller’s position.

**Dual-laser editing**: make both your lasers intersect with a model then “grab” it by pulling and holding both controllers’ triggers.
* Mode 0: Move and scale the model accoding to your controllers’ rotations.
* Mode 1: Rotate model according to your controllers’ relative positions.

# Miscellaneous

**Left-bumper + left-trigger**, or **right-bumper + right-trigger:** show/hide UI.

**Button 3 on either controller:** Show/hide magnification window in VR display mode.

**Taking off and putting on avatar attachments:** Grab an attachment per model editing and move it so that it is a normal model in the world and no longer an attachment; or grab an in-world model and make it an attachment by moving it close to one of your avatar’s joints.

**squeezeHands.js**: This script makes your avatars’ hands clench as you pull the Hydra’s triggers.