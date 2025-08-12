Kick live  is a sleek, interactive web app designed to help students and casual football (soccer) leagues easily create teams, schedule matches, and track live scores in real-time.
The app offers a user-friendly interface with smooth animations and optional WebSocket support for real-time synchronization across browsers.

Features
-Team Builder:
Create and manage multiple teams by entering a team name and a short tag (3-4 letters). Easily clear all teams and reset your workspace.

-Match Setup:
Select home and away teams from the created team list to start a live match. Prevents selection of the same team on both sides.

-Live Score Tracking:
Update scores manually with goal buttons for home and away teams. View scores in a clear scoreboard layout with team names and tags.

-Match Timer:
Built-in timer to track match duration, automatically starting and pausing with the match lifecycle.

-Auto-play Mode:
Simulate match events randomly with an auto-play button, making the match more dynamic and engaging.

-Match History:
Keep a log of past matches with scores, dates, and notes. Click on past matches for detailed match info.

-Animated Soccer Pitch:
Includes a visually appealing animated soccer ball with bounce effects and goal celebration animations (confetti).

-Goal Pulse Animation:
A goal pulse effect visually highlights when a goal is scored.

-Local Persistence & Optional Realtime Sync:
Data is saved locally using localStorage to persist teams, match status, and history. Optionally supports WebSocket connection for syncing data across multiple clients.

-Responsive Design:
Mobile-friendly layout adjusts grid and font sizes for smaller screens.



Technologies Used
- HTML5 & CSS3:
Clean semantic markup with modern CSS for styling, animations, and responsive design.

- Vanilla JavaScript:
Handles all app logic, including team and match management, UI updates, animations, localStorage persistence, and optional WebSocket integration.

- WebSocket (Optional):
For real-time synchronization across multiple users/devices when connected to a WebSocket server.



How to Use
1. Create Teams: Enter a team name and a short tag, then click "Create Team." The team will appear in the saved teams list.
2. Select Teams for Match: Choose home and away teams from the dropdown selectors.
3. Start Match: Click "Start Match" to begin tracking the live score and timer.
4. Update Score: Use the "+ Goal Home" and "+ Goal Away" buttons to update scores.
5. Auto-play: Click "Auto-play" to let the app simulate scoring randomly. Click again to stop.
6. End Match: Click "End Match" to finish and save the match to history.
7. View History: Scroll through past matches on the right panel and click to view details.

