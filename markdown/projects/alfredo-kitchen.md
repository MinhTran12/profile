# Alfredo's Kitchen

Alfredo's Kitchen is a serious game with the goal of teaching the players food safety training, especially for those who want to work in a restaurant setting. The game demo currently consists of a single level teaching the players about food storage in the kitchen.

![](images\alfredo-kitchen\intro-screen.png)

## Rearch and Design

There exists other serious games about food safety. Alfredo's Kitchen draws inspriration conceptually from SafeConsume and Ninja Kitchen, both good games of the genre.

The game's content is based on Hazard analysis and critical control points (HACCP), a system for preventing food hazard in production processes. Specifically, we used the HACCP training modules from Koninklijke Horeca Nederland (KHN) as the guide.

At the start of the design process, the team discussed potential gameplay mechanics and features we found interesting and fun. When prototyping our game physically using paper, we opted for a top-down first-person view of the kitchen, in which the player can interact with each individual object. Though later as we began developing the low-fidelity prototype, we transitioned to a third-person view where the player controls their avatar to move around the kitchen. An NPC named Alfredo was also created to be the head chef of the game's titular kitchen, and would act as the mentor for our player.

<div class="double-img">
    <img src="images\alfredo-kitchen\paper-prototype.jpg">
    <img src="images\alfredo-kitchen\lowfi-ui.png">
</div>

![](images\alfredo-kitchen\lowfi-prototype.png)

## Implementation

The high-fidelity demo was implemented using the Unity game engine, with both a gamepad and keyboard-based control scheme. The input method serves as a simple interface with the game environment, where the player controls an avatar from a top-down third-person view to navigate and interact with the surroundings. The models are made in Blender, and the artworks along with the UI followed a simple yet cute pixelated aesthetic.

The core gameplay loop revolves around the player picking up food ingredients and placing in them in the correct locations within the kitchen. Identifying correctly the food type, the storage temperature, and the storage area is key; upon a succesful or failed storage, the player will gain and lose points accordingly. Also, there is a tutorial mode where Chef Alfredo will guide the player, giving compliments if they complete tasks successfully, and lightly scolds them if they make a mistake. Then there is the challenge mode where the player try to complete as many storage tasks as possible to get a high score within a limited time.

<div class="double-img">
    <img src="images\alfredo-kitchen\gameplay-1.png">
    <img src="images\alfredo-kitchen\gameplay-2.png">
</div>

## Evaluations

We conducted two different evaluations while developing the game. The first evaluation was conducted as a "think-aloud" study with 6 participants followed by an interview. We observed how they played the game, took note of their thoughts as they played, and asked them further questions. Based on their actions and feedbacks, we identifed areas of improvement for the demo, such as lack of instructions regarding game control, and how certain objects were difficult to identify.

With the finalized demo, the team conducted the second evaluation by asking volunteers to play Alfredo's Kitchen and do a survey before and after playing; we aimed to understand player's gameplay experience as well as whether their knowledge of food safety would improve after playing the game. 22 participants were recorded, and it was found that:

1. Alfredo's Kitchen is effective in increasing the player's knowledge of proper food storage as players performed statistically better on the knowledge test after playing the game.
2. The player experience is characterized by a performative challenge, which arises from the game requiring quick and accurate actions.
