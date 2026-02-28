# Car Racing Game Prompt

Build a complete browser-based 2D car racing game using only **HTML, CSS, and JavaScript** in a single file.

## Game Requirements
- The player controls a car using keyboard input:
  - `Left Arrow` / `A` to move left
  - `Right Arrow` / `D` to move right
- The road scrolls continuously to simulate movement.
- Enemy cars spawn from the top and move downward.
- Collision with an enemy car ends the game and shows a **Game Over** screen.
- Include a **score system** that increases over time.
- Increase difficulty gradually by:
  - speeding up enemy movement
  - increasing enemy spawn rate
- Add a **Restart** button to start a new game without reloading the page.

## Visual & UX Requirements
- Clean arcade style UI.
- Show:
  - current score
  - best score (saved with `localStorage`)
  - start screen with instructions
- Responsive layout for desktop and mobile.
- Smooth animation using `requestAnimationFrame`.

## Code Quality Requirements
- Keep code organized with clear sections:
  - setup
  - game state
  - rendering
  - input handling
  - collision detection
  - game loop
- Use descriptive variable and function names.
- Add concise comments for non-obvious logic.
- No external libraries or frameworks.

## Output Format
- Return one full, runnable HTML file.
- Ensure it runs correctly by just opening the file in a browser.
