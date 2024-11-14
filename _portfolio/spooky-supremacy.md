---
title: "Spooky Supremacy"
excerpt: "A 2v2 FPS LAN game built in Unreal Engine 4"
header:
  image: /assets/images/portfolio/spooky-supremacy/7.png
  teaser: /assets/images/portfolio/spooky-supremacy/7.png
sidebar:
  - title: "Role"
    text: "Network and gameplay programming"
  - title: "Project type"
    text: "University"
  - title: "Status"
    text: "Completed"
---

Spooky Supremacy is a multiplayer game developed as part of a year long module in my final year. The module has programmers and designers form teams and make any game from the concept phase all the way to a playable demo.

Our team is made up of four programmers and is therefore focused on technical aspects, although I did use my knowledge of games design from my placement year in order to lead the creation of a games design document.

Our game is a 2v2 four-person shooter played over LAN, where one player on each team plays as a human, and the other plays as a ghost. The goal for a human is capture the domination points on a map and eliminate enemies, whereas the goal of the ghost is to interact with traps placed on the map to hinder the other team’s progress.

My roles for this project included:

- Providing my knowledge of games design to make an efficient games design document
- Creating the front-end UI for the menus, including the Host and Join screens and the Player Options menu
- Implementing a game profile system for player’s to change their display name and avatar image (from a predefined set)
- Implementing the network itself, which includes:
- Creating a lobby map, where players spawn as they change their characters and wait for the host to set up the game. This map uses blocking volumes to keep the players on the map, as well as a day/night cycle.
- Creating a game server.
- Allowing clients to join the server over LAN.
- Multiple characters for players to choose from and updating the players.
- A chat system, which allows the players to chat in the lobby/game.
- Host tools for the host to change the map and time length, as well as kick players from the game. This updates live for connected players.
- Server travel and loading screens.
- Error messages for unsuccessful client connections.
- Replicating game assets reliably across the network
- Fixing network and gameplay issues.

{% include figure popup=true image_path="/assets/images/portfolio/spooky-supremacy/1.png" alt="Image of the avatar options screen when no user profile is present" caption="This screen appears asking the user to set up their profile if no save data is found" %}

{% include figure popup=true image_path="/assets/images/portfolio/spooky-supremacy/2.png" alt="Image of the avatar options screen with user data present" caption="An example of the profile screen with a player name and avatar image" %}

{% include figure popup=true image_path="/assets/images/portfolio/spooky-supremacy/3.png" alt="Image of the host game screen" caption="The Host menu. Allows the user to set the server's name and number of players (between two and four).  The connection type is greyed out for the purpose of this build, but could be expanded to include systems such as Steam." %}

{% include figure popup=true image_path="/assets/images/portfolio/spooky-supremacy/4.png" alt="Image of the find game screen" caption="The Find Game screen. Allows users to connect to servers with spaces (only if they are still in the lobby)." %}

{% include figure popup=true image_path="/assets/images/portfolio/spooky-supremacy/5.png" alt="Image of the host's lobby screen" caption="The host's lobby screen. This screen differs depending on if the player is the server or the client (clients have a "change status" button in lieu of the Start Session and Game Settings buttons).  This screen allows hosts to start the game, change the game settings and kick players from the lobby. All players can select characters.  The lobby menu also features chat and can have its visibility toggled by pressing T." %}

{% include figure popup=true image_path="/assets/images/portfolio/spooky-supremacy/6.png" alt="Image of the select character menu" caption="The Select Character screen.  As only one character type can be chosen at a time, a selected character is greyed out and cannot be selected by other players.  The lobby updates all players when anyone changes their character, deselects a character or leaves the lobby." %}

{% include figure popup=true image_path="/assets/images/portfolio/spooky-supremacy/7.png" alt="Image of a red human character in the game world" caption="A red human in the game world.  A human's job is to eliminate the enemy team. They can also capture domination points for their team.  Besides WASD and mouse, characters are equipped with flashlights (activated by pressing F) and can change the camera zoom (by scrolling the mouse wheel)." %}

