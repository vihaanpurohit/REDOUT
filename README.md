# REDOUT

**REDOUT** is a minimalist, fast-paced browser survival game built with HTML, CSS, and vanilla JavaScript. Control a single white pixel, avoid the red obstacles, and survive as long as possible.

## Features

- **One-touch controls:** Tap, click, or press the pointer to change direction.
- **Progressive difficulty:** Your movement speed increases the longer you survive.
- **Live timer and score:** Track your survival time during each run.
- **Best score and stats:** Save your best time and gameplay statistics in your browser.
- **Trail customisation shop:** Unlock trail colours using coins earned during gameplay.
- **Achievements:** Unlock milestones for games played, survival time, turns, and more.
- **Daily challenges:** Work toward daily gameplay goals.
- **Sound and vibration controls:** Toggle audio feedback and supported device vibration.
- **Responsive canvas:** Play in desktop and mobile browsers.
- **Dark neon visual style:** Black background, glowing red obstacles, particles, and a splash screen.

## How to Play

1. Open the game.
2. Select **PLAY**.
3. Tap, click, or press anywhere on the game area to turn.
4. Avoid colliding with red obstacles.
5. Survive as long as possible and try to beat your best time.

The player wraps around the edges of the screen. Red obstacles move around the play area, and touching one ends the run.

## Controls

| Action | Control |
| --- | --- |
| Change direction | Tap or click the game area |
| Toggle sound | Use the speaker button |
| Toggle vibration | Use the vibration button (on supported devices) |
| Restart after game over | Select **PLAY AGAIN** |
| Return to the main menu | Select **HOME** |

## Run Locally

No build tools, package installation, or server are required.

1. Download or clone this repository.
2. Make sure the HTML file is named `index.html` (recommended for GitHub Pages).
3. Open `index.html` in a modern web browser.

## Deploy with GitHub Pages

1. Upload the game file to the root of your GitHub repository.
2. Rename it to `index.html` if it has another filename.
3. Open the repository on GitHub and go to **Settings → Pages**.
4. Under the build and deployment settings, choose **Deploy from a branch**.
5. Select your main branch (often `main`) and the root folder (`/`).
6. Save the settings and wait for GitHub Pages to publish the site.
7. Open the URL shown in the Pages settings.

## Data and Privacy

REDOUT stores game progress and preferences in the browser's `localStorage`, including best score, games played, deaths, total survival time, turns, streaks, coins, trail colour, achievements, daily challenge progress, sound, and vibration preferences.

- Data is stored locally in the browser on the device being used.
- It is not automatically synced between devices or browsers.
- Clearing browser storage may erase saved progress.
- The game does not require an account or a backend server.

## Built With

- HTML5
- CSS3
- Vanilla JavaScript
- HTML Canvas API
- Browser Local Storage API
- Web Audio API
- Vibration API (where supported)

## Notes

- For the best experience, use an up-to-date browser.
- Sound and vibration support varies by browser and device.
- The game is designed to run as a static website; no server-side code is needed.

## License

No license is specified in this repository yet. If you plan to make the project open source, add a `LICENSE` file with the license you choose.
