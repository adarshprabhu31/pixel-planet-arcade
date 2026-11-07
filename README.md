# Pixel Planet Arcade

A responsive, dependency free arcade site with 20 instant-play mini games. The games run in the browser and the catalogue is designed to grow over time.

## Run locally

Open `index.html` in a modern browser. No install or build step is required.

## Publish with GitHub Pages

1. Create a GitHub repository and push this project to its `main` branch.
2. In the repository settings, open **Pages** and select **GitHub Actions** as the build and deployment source.
3. The included workflow deploys the site after each push to `main`. The first deployment appears in the Pages settings when the workflow finishes.

## Add a game

Add a catalogue entry to the `games` array near the top of the script in `index.html`, then add its game id to the `startGame` switch and implement its function. Keep game state local to that function, draw into the shared stage, and set `cleanup` for any timers or animation loops so closing the game stops it.

## The 20 games

Neon Snake, 2048, Memory Match, Simon Says, Whack-a-Mole, Quick Draw, Tic-Tac-Toe, Rock Paper Scissors, Word Scramble, Math Sprint, Connect Four, Minesweeper, Pong, Breakout, Flappy Star, Number Guess, Color Match, Pattern Tap, Asteroid Dodge, and Word Blitz.
