# Team Scorekeeper — Basketball V2

A courtside basketball scorekeeper for the Naches Learning Hub, designed for middle-school student managers and coaches. A/B/C squad roster management, match statistics, and season reports are included.

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
