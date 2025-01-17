# VRgarden tutorials: Interaction with Controllers

There are many ways of doing interaction with objects and the easiest is through the Direct Interactor (hand) and the Interactable (object) through the event system (select, hover, …). Sometimes, you want to use the joystick to do a specific interaction. It’s not recommended as it is confusing the user between the immersive interaction (diegetic) and the joystick interaction (non diegetic - the controllers are not in the scene, they are outside). However, for professional applications, it can be useful. Here are some information about the names of the controllers parts and how they can be used in Unity with minimal programming.

## Features

<table cellspacing="0" cellpadding="0" class="t1">
  <tbody>
    <tr>
      <td valign="middle" class="td1">
        <p class="p3"><b>Input Feature</b></p>
      </td>
      <td valign="middle" class="td2">
        <p class="p3"><b>Feature</b></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p3"><b>Vive</b></p>
      </td>
      <td valign="middle" class="td4">
        <p class="p3"><b>Oculus</b></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p3"><b>Unity (default)</b></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td6">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td4">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><br></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td1">
        <p class="p5">trigger</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p5">Button / Axis</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p5">Trigger</p>
      </td>
      <td valign="middle" class="td4">
        <p class="p5">Trigger</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p5">I / Activate</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td1">
        <p class="p5">grip</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p5">Button / Axis</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p5">Grip</p>
      </td>
      <td valign="middle" class="td4">
        <p class="p5">Grip</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p5">I/ Select</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td1">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td4">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><br></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td1">
        <p class="p5">primaryButton</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p5">Button</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p5">System button</p>
      </td>
      <td valign="middle" class="td4">
        <p class="p5">Primary (X/A)</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><br></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td7">
        <p class="p5">secondary Button</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p5">Button</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p6">n/a</p>
      </td>
      <td valign="middle" class="td4">
        <p class="p5">Alternative (Y/B)</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><br></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td1">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td4">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><br></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td7">
        <p class="p5">gripButton<span class="Apple-converted-space"> </span></p>
      </td>
      <td valign="middle" class="td2">
        <p class="p5">Button</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p5">Grip Press</p>
      </td>
      <td valign="middle" class="td4">
        <p class="p5">Grip Press</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><br></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td7">
        <p class="p5">triggerButton</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p5">Button</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p5">Trigger Press</p>
      </td>
      <td valign="middle" class="td4">
        <p class="p5">Trigger Press</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><br></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td7">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td4">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><br></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td1">
        <p class="p5">primary2DAxisClick</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p5">Button</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p5">Trackpad-Press</p>
      </td>
      <td valign="middle" class="td4">
        <p class="p5">Joystick-Press</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p5">I/ Scale Toggle</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td1">
        <p class="p5">primary2DAxisTouch</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p6">Axis</p>
      </td>
      <td valign="middle" class="td3">
        <p class="p5">Trackpad-Touch</p>
      </td>
      <td valign="middle" class="td4">
        <p class="p5">Joystick-Touch</p>
      </td>
      <td valign="middle" class="td5">
        <p class="p5">L/ Move</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td1">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td3">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td4">
        <p class="p4"><br></p>
      </td>
      <td valign="middle" class="td5">
        <p class="p4"><br></p>
      </td>
    </tr>
  </tbody>
</table>

<p class="p6"><i>Note: I stands for XRI Interaction and L is stands for XRI Locomotion</i></p>

<p align="left"><img src="images/interaction01.jpg"/>
<img src="images/interaction02.png"/></p>

## Coding Overview

### Button action (true / false)

	Button action (true / false)
	public InputActionReference toggleReference = null;

	private void Awake(){
		toggleReference.action.started += Toggle;
	}

	private void Toggle(InputAction.CallbackContext context){
		action
	}
	
### Analog action (value)		
	public InputActionReference analogData = null;

	void Update()
	float value = analogData.action.ReadValue<float>();
		
## Examples

### ToggleObject (Button)

	using System.Collections;
	using System.Collections.Generic;
	using UnityEngine;
	using UnityEngine. InputSystem;
	
	public class ToggleObjectExample: MonoBehaviour
	{
		public InputActionReference toggleReference = null;

		private void Awake(){
			toggleReference.action.started += Toggle;
		}

		private void OnDestroy (){
			toggleReference.action.started -= Toggle;
		}

		private void Toggle(InputAction.CallbackContext context) {
				bool isActive = !gameObject.activeSelf;
				gameObject.SetActive(isActive);			
			}
		}

### ColorObject (Analog)

	using System.Collections;
	using System.Collections.Generic;
	using UnityEngine;
	using UnityEngine.InputSystem;

	public class ColorObject : MonoBehaviour
	{

  	  public InputActionReference colorReference = null;
  	  private MeshRenderer meshRenderer = null;

  	  void Awake()
  	  {
  		  meshRenderer = GetComponent<MeshRenderer>();
  		}

  	  void Update()
  	  {
  		  float value = colorReference.action.ReadValue<float>();
  			UpdateColor(value);
  	  }

  	  void UpdateColor(float value)
 	   {
  		  meshRenderer.material.color = new Color(value, value, value);
 	   }
	}

5. ColorObject and ToggleObject in the Inspector</b></p>

<p align="left"><img src="images/interaction03.jpg"/></p>
<p align="left"><img src="images/interaction04.jpg"/></p>

6. Next to Color Reference or Toggle Reference, choose XRI LeftHand [RightHand] Interaction /Activate [Select] Value [Nothing]

By default <b>Activate is the trigger</b> (bottom) and <b>Select is the grip button </b>(side) but it can be changed.

Activate value and Select value gives more than true/false states, they give values. Here is a list of the all choices you have under Interaction. Scale Toggle, for example, is the primary2DAxis click.

<p align="left"><img src="images/interaction05.jpg"/></p>

## Glossary
<table cellspacing="0" cellpadding="0" class="t1">
  <tbody>
    <tr>
      <td valign="middle" class="td1">
        <p class="p8">Term</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p8">Meaning</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td3">
        <p class="p4">Controller</p>
      </td>
      <td valign="top" class="td2">
        <p class="p4">A component that turns XR controller input such as a button press into interaction events like hover, or select. Also provides a way to show controller models and send haptic feedback to the controller.</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td4">
        <p class="p4">Interactor (hands)</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4">An object in a scene that can select or move another object in that scene. See Direct / Ray Interactor.</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p4">Interactable</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4">An object in a scene that the user can interact with (grab it, press it, or throw it).<span class="Apple-converted-space"> </span></p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td4">
        <p class="p4">Hover</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4">The state where an Interactor is in a valid state to interact with an object. This differs between Ray and Direct interaction.</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p4">Select</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4">The state where an Interactor is currently interacting with an object.</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td4">
        <p class="p4">Interaction Manager</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4">A manager component that handles interaction between a set of Interactors and Interactables.</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td5">
        <p class="p4">Gesture</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4">Sequences of movements that translate into an action that manipulates an interactable.</p>
      </td>
    </tr>
    <tr>
      <td valign="middle" class="td6">
        <p class="p4">Haptic</p>
      </td>
      <td valign="middle" class="td2">
        <p class="p4">Sensory or visual stimuli that is sent to the user to give feedback for interaction.</p>
      </td>
    </tr>
  </tbody>
</table>

