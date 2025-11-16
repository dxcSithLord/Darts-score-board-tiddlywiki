[![Browser Testing (Cross-Platform)](https://github.com/dxcSithLord/Darts-score-board-tiddlywiki/actions/workflows/browser-testing.yml/badge.svg)](https://github.com/dxcSithLord/Darts-score-board-tiddlywiki/actions/workflows/browser-testing.yml)

With help from Claude.ai:

I'll create a darts competition scoreboard using TiddlyWiki's HTML format. 

This will be a self-contained TiddlyWiki file with interactive scoring functionality for a darts tournament.I've created a comprehensive darts competition scoreboard in TiddlyWiki format! This scoreboard includes:

## Key Features:

**Tournament Management:**
- Add/remove players dynamically
- Support for different game types (501, 301, Cricket)
- Player statistics tracking (games won, average score, best finish)

**Live Scoring:**
- Real-time score updates
- Current player indicator
- Undo functionality for mistakes
- Bust detection for standard games

**TiddlyWiki Styling:**
- Authentic TiddlyWiki look and feel with tiddlers
- Responsive design that works on different screen sizes
- Clean, professional tournament interface

**Advanced Features:**
- Match history log with timestamps
- Automatic winner detection
- Player statistics calculation
- Keyboard shortcuts (Enter to record score)

## How to Use:

1. **Add Players**: Enter player names and click "Add Player"
2. **Start Game**: Select game type (501/301/Cricket) and click "Start New Game"
3. **Record Scores**: Enter the score thrown and press Enter or click "Record Score"
4. **Track Progress**: Watch the live scoreboard update with current scores and statistics

The scoreboard automatically handles turn rotation, win detection, and maintains a complete history of the tournament. It's perfect for pub leagues, tournaments, or casual games with friends!

## Download for Offline Use

The Darts Scoreboard is available as a standalone HTML file that works completely offline:

### Quick Download
- **[Latest Release](https://dxcsithlord.github.io/Darts-score-board-tiddlywiki/releases/darts-scoreboard-latest.html)** - Download the most recent version
- **[GitHub Releases](https://github.com/dxcSithLord/Darts-score-board-tiddlywiki/releases)** - Browse all versions

### Installation
1. Download `darts-scoreboard-latest.html` (or a specific version)
2. Save the file to your local machine (Desktop, Documents, etc.)
3. Double-click the file or open it with your browser

### Using via file:// URI
- **Windows**: `file:///C:/Users/YourName/Desktop/darts-scoreboard.html`
- **macOS**: `file:///Users/YourName/Desktop/darts-scoreboard.html`
- **Linux**: `file:///home/username/Desktop/darts-scoreboard.html`

### Features of Offline Version
- No internet connection required
- All CSS and JavaScript embedded in single file
- Works in Chrome, Firefox, Safari, Edge
- No external dependencies or CDN links
- Version information included in file header

### Important Notes
- **localStorage**: Score history may not persist when using file:// in some browsers due to security restrictions
- **Browser Compatibility**: For best results, use Chrome or Firefox
- **Updates**: Re-download to get the latest features and bug fixes

# Version 2

Perfect! I've updated the darts scoreboard with both requested features:

## New Game Type Added:
**180 Game** - A shorter, faster game format where players start with 180 points instead of 501 or 301. This allows for quicker matches and different strategic approaches.

## Mobile & Tablet Responsive Design:
The scoreboard now includes comprehensive responsive design for all screen sizes:

### Mobile Phones (Portrait & Landscape):
- Optimized button sizes and touch targets
- Stacked form controls for easier input
- Compressed scoreboard with readable font sizes
- Full-width buttons for easy tapping

### Tablets:
- Balanced layout that works in both orientations
- Appropriately sized text and controls
- Flexible grid system for the scoreboard

### Small Screen Landscape:
- Compact header to maximize content space
- Reduced margins and padding
- Optimized control layout
- Shorter match history panel

### Key Responsive Features:
- **Flexible scoreboard** that adapts to screen width
- **Touch-friendly controls** with larger tap targets
- **Readable text** at all screen sizes
- **Efficient use of space** in landscape mode
- **Scrollable content areas** where needed

The 180 Game follows the same rules as 501/301 but with a lower starting score, making it perfect for quick tournament rounds or when time is limited. Players still need to finish on exactly 0 (no bust on score of 1 unlike other formats).

The responsive design ensures the scoreboard works perfectly whether you're using it on a phone during a pub game, a tablet at a tournament, or switching between portrait and landscape orientations!
