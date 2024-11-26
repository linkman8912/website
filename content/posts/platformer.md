---
date: 2024-11-25
description: "A platformer inspired by Celeste, made in Godot."
image: "/images/platformer.png"
lastmod: 2024-11-25
showTableOfContents: false
tags: ["Godot", "Game Dev"]
title: "Platformer"
type: "post"
---
![Gameplay Screenshot](/images/platformer.png)
[This is just a little platformer I made in Godot, to learn more about how it works.](https://github.com/linkman8912/platformer) It's still very much a work in progress, but I'm trying to make walljumps and a Celeste-style dash. I've gotten the walljumps to a place I'm comfortable with, but the dash is difficult to get right. If I don't cancel the momentum at the end the character gets an unreasonable amount of upward momentum, but if I do, the dash is relatively unsatisfying.
{{< video "/videos/platformer.mp4" "my-5" >}}
I settled on removing vertical momentum at the end of a dash but not horizontal momentum. I haven't tweaked the dash velocity very much, which I will do in the future.

[Github](https://github.com/linkman8912/platformer)
