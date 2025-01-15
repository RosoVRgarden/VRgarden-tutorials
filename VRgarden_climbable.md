<p align="center"><img src="images/warehouse.gif"/></p>

# RosoVRgarden - climbable

## Introduction

1. To make a climbable object (a wall, a ladder or your own) is rather easy but requires many steps. First, make sure that both of your hands have an <b>XR Direct Interactor</b> so you are able to climb with both hands. Then, check the templates in the Assets&gt;Samples&gt;XR Interaction Toolkit &gt; [version] &gt; Starters Assets &gt; Prefabs &gt; Climb for an example. Drag the Ladder Prefab into the RosoVR scene to test.

<p align="center"><img src="images/climbable1.jpeg"/></p>



<p class="p2"><br></p>
<p class="p3">2. The ladder is organised of 5 parts, the left side, the right side, the handles and the top handle. It’s important that every parts can be accessed individually and are organised in groups of parents / children.</p>
<p class="p3"><img src="VR garden - climbable-images/Screenshot%202024-11-29%20at%2015.53.35.jpg" alt="Screenshot 2024-11-29 at 15.53.35.jpg"><img src="VR garden - climbable-images/Screenshot%202024-11-29%20at%2015.53.28.jpg" alt="Screenshot 2024-11-29 at 15.53.28.jpg"></p>
<p class="p2"><br></p>
<p class="p3">3. The Handles (Climbable) is the parent that contains all the handles. On this object, you will add the Climb Interactable componenent. Only the Y movement is allowed and the collider is set yo volume. Finally, drag the <b>XR Interaction Manager</b> from the hierarchy to the Interaction Manager space.</p>
<p class="p3"><img src="VR garden - climbable-images/Screenshot%202024-11-29%20at%2015.55.20.jpg" alt="Screenshot 2024-11-29 at 15.55.20.jpg"></p>
<p class="p3">4. For every handles, make sure that you add a capsule collider (and remove the mesh collider if there is one already).</p>
<p class="p3"><img src="VR garden - climbable-images/Screenshot%202024-11-29%20at%2015.54.37.jpg" alt="Screenshot 2024-11-29 at 15.54.37.jpg"></p>
<p class="p2"><br></p>
<p class="p3">5. In the XR Origin of your project, create an empty game object and add the <b>Climb Provider </b>component that allows every movement direction (x,y,z).<span class="Apple-converted-space"> </span></p>
<p class="p3"><img src="VR garden - climbable-images/Screenshot%202024-11-29%20at%2016.09.27.jpg" alt="Screenshot 2024-11-29 at 16.09.27.jpg"></p>
<p class="p2"><br></p>
<p class="p3">6. For a ladder, it’s important to extend it as a separate object (the top handle) so the user can move away from it. It doesn’t look very good but it is important for the correct use of VR. Also, you will need to activate the climb settings override on this particular area to allow Y movement (going up/down) but also the Z movement so the user can move back and forward and move onto a platform, for example.<img src="VR garden - climbable-images/Screenshot%202024-11-29%20at%2016.05.53.jpg" alt="Screenshot 2024-11-29 at 16.05.53.jpg"></p>
<p class="p2"><br></p>
<p class="p3">7. Designing the VR ladder</p>
<p class="p3">Although the ladder seems to only fulfil a technical requirement, there are existing design that might be interesting to copy. This is one is from the TV series Hannibal (2013-2015).</p>
<p class="p3"><img src="VR garden - climbable-images/VR%20ladder.png" alt="VR ladder.png"></p>
</body>
</html>
