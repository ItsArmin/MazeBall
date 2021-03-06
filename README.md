# MazeBall
A Unity3D puzzle game made for Oculus Rift. Scripts for object physics, control, and game logic done in C#. Desigined for Oculus hardware with specific headset functionality built out, as well.

## Summary
Made as a final project for a VR class in Spring 2017 as a student at the University of Illinois. This repo will mainly be an overview the project itself and how it works. *(Note: As of Dec. 2018, will try to add some of the codebase here, but ulitmately the project is large and designed for school, so may not be able to put too much here)*

## Background
Throughout the VR Class at the U of I, assignments and lectures all focused on various parts of VR as a whole: generalized topics like 3D vector match and computer graphics, along with more applied subjects like Unity3D development and VR experience strategies (i.e. how to reduce motion sickness, better create immersion through UX, etc.). This all culminated in building some sort of Unity3D-based experience for Oculus Rift (note: the reason for the class using Oculus Rift is that my professor, Steve LaValle, was one of the scientists at Oculus in its first few years as a company).

As a fan of video games, especially Nintendo-made ones, I pushed for making a game as the project. One thing I personally noticed with most VR experiences was that many of them aimed for immersion via a first-person view, which in some cases can work well, but if not done cleverly, can either eliminate immersion or cause motion sickness.

<img src="https://r.mprd.se/media/images/33510-Doom_(USA)-1497230017.jpg" width="400" height="300"/>
<sup><i>Doom, the first-person action video game released in 1993</i></sup>


Unlike traditional game consoles, creating a first-person action game like *Doom* isn't that straightfoward to move to VR, and simply letting the POV go through the headset while still controlling movement with a typical gamepad causes a sort of mismatch for the brain (since it sees movement, but isn't actually feeling movement), which usually causes motion sickness. One example of the opposite effect was a VR chess game, which was basically just sitting in a chair playing chess and ended up being more immersive since I was playing sitting down (yes, as silly as that may sound, a simple idea ended up being pretty clever for VR).

Our group's idea was to look towards using a more unique control schema or method of immersion, and that idea came originally from this game:

<img src="https://static.gamespot.com/uploads/original/1547/15470456/2733355-captain-toad-1.jpg" width="500" height="300"/>
<sup><i>Captain Toad: Treasure Tracker, released in 2014</i></sup>

*Capital Toad: Treasure Tracker* is a Nintendo-developed puzzle game based on the Toad character from the *Super Mario* series of games. The main gameplay is intended to callenge the fundamentals of a typical Mario platforming game by restricting movement to simply walking around (no jumping or power-ups) and have the player navigate Japanese box garden-like levels to find hidden gems and navigate to the golden Power Star. Most elements of each level are based on the perspective of the camera, which can be controlled by the player to to find objects and pathways not originally in view. *Captain Toad*'s bottom line is a game that restricts physical control and insteads centers around visual puzzles in contained, but deceptively fleshed out environments.

Our game, *MazeBall*, tries to emulate this very design philosophy by also having a simple player-controlled character (in this case, a ball that rolls around) with smaller, closed levels that focus on optical illusions and visual problem-solving to find 3 hidden gems and make it to the goal flag.

.... to be continued.


## Screenshots
(more to be added)
<img src="screenshots/Level1.png" width="800" height="600">
<img src="screenshots/Level1Back.png" width="800" height="600">
<img src="screenshots/Level2.png" width="800" height="600">
<img src="screenshots/Level2Back.png" width="800" height="600">
<img src="screenshots/Level4.png" width="800" height="600">
