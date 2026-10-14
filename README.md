# Garfield-Kart---Furious-Racing-VR
VR Mod for Garfield Kart - Furious Racing

<img width="448" height="442" alt="Adobe" src="https://github.com/user-attachments/assets/e9a790b9-a52c-473c-81b5-149531cf32e4" />

GARFIELD KART - FURIOUS RACING VR  -  VR mod (Unity 2018.4, Mono x64)
=====================================================================

Version 0.1.3 (test build).

CHANGES
-
0.1.3 - Item by your right hand: move it left / right, down / up and back / forward, and resize it, in the
        VR settings menu (Screen section).
        
      - In a race the right stick up is a second X and right stick down a second B.
        Option: [Input] RightStickUpDownXB (menus are not affected).


WHAT IT DOES
------------
* Stereo VR through OpenXR (SteamVR, Meta/Oculus Link, Virtual Desktop, WMR...).
* First person: you sit in your kart at your driver's head and turn with the kart; look around freely.
  Third person: you are where the game's camera is, behind the kart.
  Switch while racing: click the right stick (R3).
* Track / kart presentations, results and the podium: you stand at the game's camera.
* First person: the item you picked up floats by your right controller.
* **Gyro steering** (option): steer with the motion controllers - "Wheel" (hold both controllers like a steering
  wheel and turn it) or "RightHand" (roll the right controller). Straight ahead = how you hold them when the
  race starts; re-centre with both stick clicks. The stick still steers too.
* The VR controllers are an Xbox controller for the game (fed straight into the game's Rewired input).
* Menus and HUD are on a screen floating in front of you.

INSTALL
-------
1. Copy zip into the game folder (merge / overwrite).
2. Start your VR runtime first, then the game.
   
CONTROLS (the game's own gamepad layout; Xbox buttons in brackets)
--------------------------------------------------------------------
Left stick ...... steer / menus

Right stick up/down X (throw foward)/ B  (throw backwards) in a race (menus: right stick)

Right stick click . first person <-> third person

X + Y together .. Start (pause)

A + B together .... Back

Both stick clicks re-centre the view (and the gyro steering)

VR SETTINGS MENU: hold Y + left stick click for 1.7 s (view, gyro steering, item by your hand, picture...).

Everything is in BepInEx\config\garfieldkart.vr.cfg ([GamepadButtons] = what each VR control presses).


Uses the OpenXR bridge in BepInEx\plugins\GKVR (see LICENSES). Free, non-commercial.
