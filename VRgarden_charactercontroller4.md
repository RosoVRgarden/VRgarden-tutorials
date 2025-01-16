# VRgarden - Character Controller 4:
# from making you character to exporting it to Unity.

<b>Part I - Getting started with Character Controller</b></p>

<p class="p4"><span class="s1">(<a href="https://www.youtube.com/watch?v=6U7gr-IVc6U&amp;list=PLNV5zSFadPdkRZZ7WIkctjGd3HD1q8wgE"><span class="s2">https://www.youtube.com/watch?v=6U7gr-IVc6U&amp;list=PLNV5zSFadPdkRZZ7WIkctjGd3HD1q8wgE</span></a>)</span></p>

<b>Part II - Installing Unity Auto Setup</b></p>
<p class="p4"><span class="s1">(<a href="https://www.youtube.com/watch?v=GcjTYAHNe2A"><span class="s2">https://www.youtube.com/watch?v=GcjTYAHNe2A</span></a>)</span></p>

1. Get the CC Auto Setup. There should be a copy of the file in the common folder but if it’s not there or requires update you can install it yourself.

<p class="p4"><span class="s1">Go to<b> </b><a href="https://soupday.github.io/cc_unity_tools/installation.html"><span class="s2"><b>https://soupday.github.io/cc_unity_tools/installation.html</b></span></a></span></p>

2. Select URP Latest Release:</p>
https://github.com/soupday/cc_unity_tools_URP/releases/

3. Select CC/iC Unity Tools 1.6.x URP14 for Unity 2023.3 or URP17 for Unity 6.000. Click on Source Code to download the program. Unzip it on your computer.</p>

4. In Unity, go to Windows/Package manager and click on + and select add package from disk. Find the folder you have unzipped and select the package.json file.<span class="Apple-converted-space"> </span></p>

<p align="left"><img src="images/character01.jpg"/></p>

The installation will start and you will get a new menu called Reallusion.</p>

<p align="left"><img src="images/character02.jpg"/></p>

<b>Part III Character Export<span class="Apple-converted-space"> </span></b></p>
<p class="p4"><span class="s1">(source: <a href="https://www.youtube.com/watch?v=EwdMSC8UjSY"><span class="s2">https://www.youtube.com/watch?v=EwdMSC8UjSY</span></a></span></p>

1. Once your character is ready and the Unity project is setup, you can export the character from CC4. Go to file &gt; export &gt; clothed character (I’m using Kevin as an example).<span class="Apple-converted-space"> </span></p>

2. In the export dialogue, select <b>Unity 3D</b>, <b>Mesh and Motion</b>, <b>Current Animation (ALL)</b>, <b>Delete Hidden faces</b> and <b>enable Subdivision Meshes</b>.<span class="Apple-converted-space"> </span></p>

3. Next, import the files from your computer. You should have 4 folders/files. Kevin.fbm, textures, Kevin.fbx and Kevin.json.</p>

4. Go to the Reallusion menu and select import character. You will have series of option to import your character where Reflexive SSR eyes, Two Pass hair and Everything (under features) are the best quality. Then click build material.<span class="Apple-converted-space"> </span></p>

5. You can then drag your character from the prefab folder to the scene (Kevin.prefab).</p>

6. You can tweak the material in the inspector (normal on the skin, roughness, skin colour, hair colour, ...) or tweak the face movements by selecting the CC_Base_Body prefab under Kevin. In the inspector, they are under <i>Blendshape</i>. 

<b>Part IV Import Multiple Animations (or Motions)</b></p>
<p class="p4"><span class="s1">(see <a href="https://www.youtube.com/watch?v=tgirPjknAv4&amp;t=57s"><span class="s2">https://www.youtube.com/watch?v=tgirPjknAv4&amp;t=57s</span></a>)</span></p>

1. You can import multiple animations. Find the animation tab, right click on one of the animation and select find file to locate them on your hard drive. Copy the entire file structure and go to FBX export menu (see 1).</p>
2. Select Unity 3D and only Motion this time. Then go to Custom, click on the folder icone with an arrow and paste the file structure you have just copied. Select the animation(s) that you need and deselect First Frame in Bind Pose option.
3. As you import the FBX in Unity, you need to go to the Rig panel and select Humanoid. import from other avatar and import from other avatar (select Kevin). you can select Kevin and see the motions. <span class="Apple-converted-space"> </span></p>