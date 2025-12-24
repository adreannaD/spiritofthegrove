Spirit of the Grove:
Spirit of the Grove is a first-person fantasy RPG prototype built in Unity where players cleanse corrupted shrines, survive enemy ambushes, and restore balance to a mystical grove through exploration, combat, and progression. Play the game on 
Unity Play: https://play.unity.com/en/games/881e9773-0e7c-4029-af40-91c1080466b5/builds

Gameplay Overview:
Players explore interconnected shrine areas and return to the central grove. Shrines are activated using collected Spirit energy, which also triggers enemy ambushes. Players unlock the final portal and complete the journey to win. The game emphasizes player agency, environmental storytelling, and combat-driven progression.

Core Systems Implemented:
The game includes a player combat system with Spirit Bolt and Spirit Burst abilities, health management, and respawn handling. Enemy AI uses NavMesh movement, shrine-bound aggression, melee combat, knockback reactions, and loot drops. Shrines consume Spirit to activate, restore health, and trigger quests. Dialogue-driven storytelling is delivered through dragon NPCs, and collectible heart gems and portals provide interaction and progression. The final win condition is displayed via a “You Win!” screen.

Design Focus:
The game focuses on alternating exploration, dialogue, and combat to maintain pacing. Enemy ambushes provide moments of surprise and challenge. Storytelling is conveyed through environment and character interactions without cutscenes.

Built With:
Unity (URP), C#, NavMesh AI, Unity Input System, AudioSource, and UI systems. Version control is managed with Git and Git LFS.

Repository Notes:
This repository contains the Packages, and ProjectSettings folders. Generated Unity folders such as Library and Temp are excluded via .gitignore.

What I Learned:
Developing this project helped refine scalable quest and dialogue systems, debugging NavMesh and runtime spawning issues, managing large Unity projects with Git and Git LFS, and integrating third-party assets into custom gameplay logic.
