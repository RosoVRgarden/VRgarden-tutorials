# VRgarden - VR Builder

VR Builder is a tool to easily prototype VR interaction for training or other industrial purposes. It can also be used creatively in order to reduce the amount of code necessary in your application. An example is getting a key (a grabable object), put the key in a keyhole and open the door automatically. In this tutorial, you will learn the basics so you can use this tool and also decide whether it can do what you need.<

1. First. Use the package manager to instal VR Builder and, optionally, another package called States and Data that is available in the VRgarden lab.

<p align="left"><img src="images/builder01.jpg"/></p>

2. Once installed, VR Builder can help you setup your project then your scene. Remember that you are using OpenXR. You can either do it at the beginning and open the demo to look at the various possibilities that the package offers. To find the menu again, go to Tools &gt; Project Setup Wizard.

3. After looking at the demo, you can setup your own scene using Tools &gt; Scene Setup Wizard. All parameters are good, click on the Finish button. Then, in process editor, right click, select new and Step. Select the step in the editor and choose a Behaviors / Transitions / Unlocked Objects. Have a look at the possibilities:
<br>
</p>
<table cellspacing="0" cellpadding="0" class="t1">
  <tbody>
    <tr>
      <td rowspan="17" valign="middle" class="td1">
        <p class="p4"><b>Behaviors</b></p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4">Animation</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4"><b>Move Object</b></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Scale Object</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p4">Environment</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Disable Component</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Disable Objects</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Enable Component</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Enable Objects</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Start Particle</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Stop Particle</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Unsnap Object</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p4">Guidance</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4"><b>Highlight Object</b></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4"><b>Play Audio File</b></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Play Text-to-Speech</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Spawn Confetti</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p4">State and Date (optional)</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Set Value / Trigger ...</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p4">Utility<span class="Apple-converted-space"> </span></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Behaviors Sequence</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4"><b>Delay</b></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td2">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4">Set Parent</p>
      </td>
    </tr>
  </tbody>
</table>
<p class="p2"><br></p>
<table cellspacing="0" cellpadding="0" class="t1">
  <tbody>
    <tr>
      <td rowspan="10" valign="middle" class="td4">
        <p class="p4"><b>Transitions</b></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4">Environment</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4">Move Object in Collider</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4">Object Nearby</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p4">Interaction</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><b>Grab Object</b></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4">Release Object</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><b>Snap Object</b></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4">Touch Object</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p5"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4">Use Object</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p4">State and Date (optional)</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4">Check / Compare</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p4">Utility</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4">Timeout</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p4">VR User</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4">Teleport</p>
      </td>
    </tr>
  </tbody>
</table>

4. The most important are the Transitions. In the example above, to grab a key, it’s an Interaction &gt; Grab Object. You can then drag the model of your key from the hierarchy into the menu. If the key doesn’t have an XR grabable, you can add one using <b>Fix it</b>.

<p align="left"><img src="images/builder02.jpg"/></p>

5. The next step is to create the area where the key will need to be brought. It’s also a transition, this time it’s a Snap Object transition where you have the object (the Key) and a place to snap it (Snap Zone). You can create a Snap Zone by going to the object in the hierarchy and create a Snap Zone. You can then move the Snap Zone where you need it (the key hole in this situation).<span class="Apple-converted-space"> </span></p>

<p align="left"><img src="images/builder03.jpg"/></p>
<p align="left"><img src="images/builder04.jpg"/></p>

6. To open a door, it’s a behaviors. Choose the Animation &gt; Move Object. In order to move the object, drag the object into the object field and create an empty object with the transform that carries the value of rotation. Then add the time of the animation (2 s).

<p align="left"><img src="images/builder05.jpg"/></p>

7. There could be other objects in the room to grab. If the user makes a mistake, you can tell them by creating an alternative path.</p>

<p align="left"><img src="images/builder06.jpg"/></p>

Making a mistake can trigger an audio and highlight the correct object very training style, not recommended).

<p align="left"><img src="images/builder07.jpg"/></p>

<p align="left"><img src="images/builder08.jpg"/></p>

8. It doesn’t end with one task, you can setup other tasks after this one is finished by creating a new chapter (left) and linking the end of task to that new chapter (process editor)</p>

<p align="left"><img src="images/builder09.jpg"/></p>

<p align="left"><img src="images/builder10.jpg"/></p>

9. User manual: <a href="https://www.mindport.co/vr-builder-manual/online-documentation"><span class="s2">https://www.mindport.co/vr-builder-manual/online-documentation</span></a></span></p>

