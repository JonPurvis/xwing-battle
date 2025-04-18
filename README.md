# X-Wing Battle :rocket:

[X-Wing Battle](https://jonpurvis.github.io/xwing-battle/) is a thrilling 2D space shooter built using GROK. No part of the code was wrote by a human.

You pilot an X-Wing fighter in a galaxy far, far away, battling Imperial TIE Fighters and a formidable TIE Boss. Destroy enemies to rack up points, collect droid powerups for special abilities, and survive as long as possible. With retro arcade vibes and a Star Wars-inspired aesthetic, this game offers smooth controls, dynamic visuals, and immersive gameplay.

![X-Wing Battle Screenshot](https://raw.githubusercontent.com/JonPurvis/xwing-battle/refs/heads/main/readme_image.png)

## Features :star:

**Engaging Gameplay**: Control an X-Wing to shoot down TIE Fighters (25 points each) and a TIE Boss (200 points) while dodging collisions.

**Powerups**: Collect droids for 10-second powerups:
- Boost: Increases ship speed
- Fast Shot: Reduces shooting cooldown for rapid fire.
- Scatter Shot: Fires a ring of bullets in all directions.
- Helping Hand: Spawns a friendly ship that flies in, assists for 10 seconds, and flies away.

**Lives and Scoring**: Start with 6 lives, lose 1 per TIE Fighter collision or 2 per TIE Boss collision, and gain an extra life every 250 points for the maximum of 6 lives.

**Dynamic Enemies**: TIE Fighters move at speed 0.7, TIE Boss at 0.5, with fleeing behavior (speed 2) when the boss spawns.

**Audio Effects**: Retro sounds for shooting, explosions, and powerup collection.

## How to Play 👾

Playing X-Wing Battle is as easy as going to https://jonpurvis.github.io/xwing-battle/ and playing it in your browser.

1. Start the Game:
   - On the start screen, click Start Game to play or Instructions to view the guide.
   - The instructions feature a scrolling text crawl and a Back button to return to the start screen.

2. Play:
   - Destroy TIE Fighters and the TIE Boss to earn points.
   - Collect droid powerups for temporary advantages.
   - Avoid enemy collisions to preserve lives.
   - Earn extra lives at 250-point intervals (up to 6 lives).

3. Game Over:
   - When all lives are lost, the game over screen displays your score, play time, and enemies killed.
   - Click Play Again to return to the start screen.

### Controls 🎮

| Action        | Keys                | Description                                                      |
|---------------|---------------------|------------------------------------------------------------------|
| Thrust        | W / Up Arrow        | Move forward (speed 2.5, or 3.75 with Boost)                     |
| Rotate Left   | A / Left Arrow      | Rotate counterclockwise (0.03 rad/frame)                         |
| Rotate Right  | D / Right Arrow     | Rotate clockwise (0.03 rad/frame)                                |
| Shoot         | Spacebar            | Fire blue laser blasts (0.5s cooldown, or 0.2s with Fast Shot)   |

## Contributions 🤝

Contributions are welcome! Don't write any code yourself though, this should be a game purely built using AI (GROK). Use the power of prompts to get GROK to add new features and fix bugs.

Any contribution should be made by forking this repository and then creating a branch and opening a Pull Request. Once merged, GitHub pages will build and deploy a new version of the game to be played in the browser. 
   
