---
title: "009: Big bug in procedural gen map, added fanofknives ability"
date: 2025-09-19T06:58:27.110Z
image: /assets/uploads/skærmbillede-2025-09-19-081646.png
---
## Focus from last week

This will require some careful consideration, as I need to think through how the system should be structured and how it will integrate with the rest of the game. Part of this process will involve looking into which **systems development artifacts** can be applied to support the design, such as diagrams, models, or structured documentation.

The goal is to create a clear foundation before starting implementation, ensuring that the upgrade system is both scalable and flexible enough to support future additions.

## What have I worked on this week?[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#what-have-i-worked-on-this-week "Permalink")

This week was originally supposed to be focused on creating new weapon abilities, but I ran into a bug in my procedurally generated map that ended up taking me three full days to fix. Despite that setback, I still managed to implement a new ability: *Fan of Knives*. It was a great learning experience, since I not only solved a tricky problem with the map generation system but also made progress on expanding the gameplay.

![](/assets/uploads/skærmbillede-2025-09-19-081646.png)

## What have I learned?[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#what-have-i-learned "Permalink")

Because I ran into a navigation bug with my procedurally generated map, I ended up learning a lot about baking navigation in Godot. While working on this issue, I also decided to install Visual Studio Code to explore what it can offer compared to the standard Visual Studio. One of the main reasons for trying it out is that VS Code has built-in integrations for Godot as well as support for GDScript, which makes the development workflow smoother.

## What challenges did I face?[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#what-challenges-did-i-face "Permalink")

Before I started working with procedurally generated maps, I used to bake navigation data directly into the tileset. However, with procedural generation I now had to figure out how to bake the navigation through code *after* the map was created. This turned out to be quite a challenge, since there was very little information available on the topic— even ChatGPT struggled to give me a clear answer. After a lot of trial and error, I finally managed to solve it and gained a much deeper understanding of how Godot handles navigation.

On the other hand, implementing the *Fan of Knives* ability was actually pretty straightforward compared to the navigation system. It was a nice contrast: one part of development felt like exploring uncharted territory, while the other was smooth and quick to set up.

## How have I contributed to the project?[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#how-have-i-contributed-to-the-project "Permalink")

fixed navigation bug, and created fanofknives ability

## Machine Learning and AI:[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#machine-learning-and-ai "Permalink")

No progress has been made

## Next steps / focus for next week[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#next-steps--focus-for-next-week "Permalink")

For next week, my main goal is to implement a system that selects abilities at random, adding more variety to the gameplay. I also plan to put *Fan of Knives* on a cooldown timer so it feels more balanced and strategic to use. On top of that, I’m considering adding gold as a resource that can spawn in chests and drop when the player dies, rather than dropping from enemies. This should create a more consistent and rewarding progression system.

## Reflection[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#reflection "Permalink")

That navigation bug almost drove me insane. I spent countless hours repeating the same steps over and over, trying to figure out what was wrong. Then suddenly, after changing just one small detail, everything started working. It was both frustrating and relieving at the same time. Looking back, I realize I need to get better at stepping away from the work and taking breaks instead of stubbornly grinding at the same problem for too long.

## Links & Sources

https://medium.com/pumpkinbox-blog/procedural-map-generation-with-godot-part-1-1b4e78191e90


https://medium.com/pumpkinbox-blog/procedural-map-generation-with-godot-part-2-dc8196cc3e57


https://kidscancode.org/blog/2018/08/godot3_procgen1/


https://github.com/gdquest-demos/godot-procedural-generation


https://forum.godotengine.org/t/pathfinding-with-procedural-generation/81321