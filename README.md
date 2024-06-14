# POSTECH Evacuate
A Fire Escape Simulation w/ Unity

## Demo Video
[Full Demo](https://drive.google.com/file/d/1uUVUiMOdKrDJpqTRSA-hG9gJ2kwXiLgR/view?usp=sharing)

## Introduction
Fire safety is a critical concern within any building, especially university campuses with a high density of occupants. Familiarization with escape routes is paramount in ensuring a safe and efficient evacuation during a fire emergency. This project proposes the development of "POSTECH Evacuate", a virtual fire escape simulation tool built using Unity.

## Background and Motivation
Fire safety training currently faces limitations. Traditional methods rely on static diagrams and presentations, failing to capture the immersive experience crucial for internalizing escape routes and practicing decision-making under pressure in a real fire scenario. This passive learning approach often leads to decreased focus and poor retention of critical information. While Virtual Reality (VR) offers a more engaging and immersive training experience, its development can be expensive and complex, especially when tailored to specific building layouts and procedures. This high cost significantly hinders VR's accessibility for institutions seeking to implement such training for their staff and students.

## Implementation
Using Unity's High-Definition Render Pipeline (HDRP) and assets from the asset store, we were able to create a realistic 3D environment that mimics POSTECH’s Dormitory Building 16 (DICE). For our game mechanics, the first-person player is controlled using simple keyboard and mouse inputs, providing intuitive navigation through hallways, rooms, and staircases. We implemented dynamic fire and smoke graphics along with realistic fire alarm and siren noises, adding great realism to the game and challenging the player’s ability to think under pressure. The pink guided arrows, strategically placed throughout the environment, serve as visual cues that direct the player towards the correct evacuation route. These arrows are designed to be clear and prominent, ensuring that users can easily identify and follow them even in low-visibility conditions caused by smoke. This element is a crucial part of our escape simulation, as it teaches and familiarizes users with the building's layout , ultimately promoting fire safety awareness and preparedness within POSTECH.

## Roles & Contributions
- Nathan Bouffet (33%):
Integrated realistic fire effects and applied shaders and texture mapping to game objects
- Dylan Tran (33%): 
Created intuitive user interface and implemented character movement and navigation controls
- Megan Lee (33%): 
Researched Dormitory Building 16 (DICE) and developed accurate 3D graphic models
