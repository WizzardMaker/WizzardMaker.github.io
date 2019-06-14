---
title: Pathfinding - An Open ATD Story
categories: [update, oatd]
tags: [airlinetycoon, pathfinding, AI , development]
header:
  overlay_image: /assets/images/logoCardPost.png
---

## Welcome to the first Open-ATD blog post!

This is a goal for update [Basic gameplay](https://github.com/WizzardMaker/OpenATDeluxe/projects/1) and it "fixes" issue [#15](https://github.com/WizzardMaker/OpenATDeluxe/issues/15). The update will arrive this weekend (06.14.2019)
{: .notice--info}

Greetings everyone!
OpenATD is the reimplementation of the great video game Airline Tycoon Deluxe.

We are hard at work on making our version into a playable game, with the current release being a great step towards a real thing.

This update will bring the foundation for all characters in the game, from your own player character to the funny robot. It will also bring one of the best things about the game: the **music**. We added playback functionality for all .ogg and .mid files inside the `SOUND` folder. There is a bug in the MIDI playback, where the notes sometimes lag. This will be looked into in a future update.

### Changelog:
- Character foundation for future updates
- Navigation data for the airport
- Player movement in the airport
  - Player entering rooms and leaving them at the correct position.
- **MUSIC**
  - Now with support for ogg and midi playback (although midi is missing a good implementation)
  - The game will prioritize the ogg music files and will even play back your own songs when added as .ogg files
- Sound playback is now possible, but not implemented in a dialog system 
