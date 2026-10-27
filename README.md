# Team Scorekeeper — Basketball V2.1 (Example Team)

A courtside basketball scorekeeper for the Naches Learning Hub, designed for middle-school student managers and coaches. A/B/C squad roster management, match statistics, and season reports are included.

## Try the fictional example first

Click **Try example team** (top right) to create **Cedar Valley Wildcats · Practice Team** as a separate program. This includes **24 fictional players** divided into A/B/C squads, several opposing rosters, three completed games, and one in-progress game for practice.

- Use **Practice live game** to tap a home or visitor jersey and record shots, rebounds, assists, etc. Score and event history update instantly.
- Use **See sample reports** to explore statistics and charts.
- Use **Reset example** to discard practice changes and reload the starting example. Resetting affects only the demo program; it does not delete real teams.
- The **Program / season** selector returns to your own teams. The example is never automatically loaded over your information.
- All example names, game scores, and dates are fictional. Avoid including the demo in actual team reports.

## Game Day workflow

1. In **Teams & Rosters**, choose your program and add your A/B/C squad players.
2. Open **Game Scorekeeper** → **+ New game**. Select the squad and give the opposing school/team a name.
3. Optionally paste the opponent roster, one jersey per line: `12, Player Name` or `12`.
4. Record stats by tapping **Home / Away**, a jersey, and an event. Score updates automatically. The **TEAM SCORE** tile lets you record an opponent's made basket when the scorer is unknown.
5. Add or edit opposing players during the game as needed. Use **Undo last play** to correct mistakes.
6. View points by quarter and live box scores beneath the Game Day controls. Open **Stats & Exports** for CSV and JSON backup exports.

## Features

- Large touch-friendly jersey tiles and buttons for basketball scoring
- Opponent rosters with individual statistics, entered before or during the game
- External opponents or games between A/B/C squads
- Auto-scored points, rebounds, shooting attempts, fouls, turnovers, assists, steals and blocks
- Game clock (convenience only), period controls, play-by-play history and Undo
- Points-by-period bar charts and game shooting percentages
- Export home rosters, opponent rosters, game results, season totals, events, and a complete JSON backup
- Original V1 saved records are preserved when updating the same GitHub Pages origin and browser profile

## Installation

Upload `index.html` at the root of your `team-scorekeeper` GitHub repository, then enable **Settings → Pages** from the main branch/root. No packages or server are required.

## Important data and reliability notes

All data is stored only in the browser's `localStorage`, **not** automatically in a signed-in Google account or Google Drive. The system is not synchronized across devices and offers no password-based access controls. Back up data regularly and follow your school's requirements for handling player information and exports. This is a coaching statistics assistant, not an official game-clock or certified scorebook system. Do not rely on it as the sole record of a game.

## Team & Season Settings

The roster page has a collapsed **Manage team or season** section under **Team & season settings**. Opening it gives access to **Edit Team/Season Details** (changes only the display name and season) and **Delete Team/Season Data** (erases all rosters, games, and statistics in that one team/season). Deletion requires a confirmation plus typing `DELETE`. Export a full JSON backup before attempting to remove a team/season. This is not an authentication control: anyone with access to the same browser profile can use these options.
