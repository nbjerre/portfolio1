---
title: "010: Big bug in procedural gen map, added fanofknives ability"
date: 2025-09-26T06:29:00.947Z
image: /assets/uploads/skærmbillede-2025-09-26-083917.png
---
## Focus from last week

For next week, my main goal is to implement a system that selects abilities at random, adding more variety to the gameplay. I also plan to put *Fan of Knives* on a cooldown timer so it feels more balanced and strategic to use. On top of that, I’m considering adding gold as a resource that can spawn in chests and drop when the player dies, rather than dropping from enemies. This should create a more consistent and rewarding progression system.

## What have I worked on this week?[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#what-have-i-worked-on-this-week "Permalink")

This week I made a lot of progress on the gameplay systems. I added a cooldown to the *Fan of Knives* ability, and I also set up a system where abilities are chosen randomly from a pool of three, which makes each run feel more varied.

I created a chest with a custom animation made in Aseprite, and integrated it into the procedural map generation script so that it spawns naturally within the world. On top of that, I worked on the overall gameplay loop: now, when the player dies, a death screen appears and they are sent back to the tavern. From the tavern, the player can head back out into the world to start another run.

Finally, I also implemented a brand new ability called *Piercing Shot*. This ability adds another layer of strategy to combat and fits well with the existing set of skills."

![](/assets/uploads/skærmbillede-2025-09-26-083917.png)

## What have I learned?[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#what-have-i-learned "Permalink")

I’ve been working through a lot of relatively simple tasks, which has given me the chance to dive deep into Godot’s features and become more comfortable with the engine. Along the way, I tried switching to Visual Studio Code since it supports GDScript, but I eventually decided to go back to regular Visual Studio because VS Code presented a few challenges in my workflow.

## What challenges did I face?[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#what-challenges-did-i-face "Permalink")

For once, I didn’t run into any major obstacles. The work flowed much more smoothly this time, and it felt great to make steady progress without being held back by frustrating bugs or unexpected issues.

## How have I contributed to the project?[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#how-have-i-contributed-to-the-project "Permalink")

*Fan of Knives* now has a cooldown, abilities are chosen randomly from a pool of three, I added an animated chest to the procedural map (integrated into the generation script), implemented a full gameplay loop (death screen → return to tavern → restart), and shipped a new ability: *Piercing Shot*.

## Machine Learning and AI:[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#machine-learning-and-ai "Permalink")

No progress has been made

## Next steps / focus for next week[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#next-steps--focus-for-next-week "Permalink")

Next week, my main focus will be on creating several new weapon abilities. Expanding the ability pool will not only add more variety to the combat but also make each run feel more unique and replayable.

## Reflection[](https://portfolionbjerre.netlify.app/006-feedback-from-po-astar-algorithm-and-procedural-generated-maps/#reflection "Permalink")

This has been a fantastic week—if only every week could be like this one. It feels great to have spent so much time working with Godot’s systems, from scenes to scripting and beyond. The more I use the engine, the more comfortable and confident I become with its workflow.

## Links & Sources

https://docs.godotengine.org/en/latest/tutorials/navigation/navigation_using_navigationmeshes.html


https://forum.godotengine.org/t/pathfinding-with-procedural-generation/81321


https://github.com/gdquest-demos/godot-procedural-generation


https://gamedevacademy.org/godot-procedural-generation-tutorial/


https://kidscancode.org/godot_recipes/3.x/ui/cooldown_button/index.html


https://forum.godotengine.org/t/im-trying-to-make-a-cooldown-for-an-action-for-a-game-how-do-i-code-it/512


https://www.youtube.com/watch?v=QFICFcD5pUI          ← Timers and Cooldowns in Godot 4


https://www.youtube.com/watch?v=nnMu8s8RlYM            ← Godot Top-down Shooter Tutorial — Cooldown


https://www.youtube.com/watch?v=MMIY_Fdg-nA            ← Navigation mesh / terrain nav in Godot demo


https://forum.godotengine.org/t/procedural-generation-for-a-2d-roguelike/44783