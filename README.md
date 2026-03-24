# Card Wars

A small front-end project inspired by the *Card Wars* style from *Adventure Time*.

This project currently focuses on the visual side of the game experience: a title screen, a game screen built around BMO, and themed card layouts using local image assets.

## Preview

- Title screen with retro-styled start and quit buttons
- Game screen with:
- BMO-inspired interface
- Player and opponent card rows
- Action buttons
- Meld/card display area
- Local image-based card assets

## Built With

- HTML5
- CSS3
- Google Fonts (`Press Start 2P`)

## Project Structure

```text
Card Wars/
├── game.html
├── title-Screen.html
├── images/
├── scripts/
└── styles/
    ├── title-Screan.css
    └── BMO/
        ├── bmo.css
        ├── game.css
        └── player-actions.css
```

## How to Run

Because this is a static front-end project, no installation is required.

1. Clone or download the repository.
2. Open `title-Screen.html` in your browser to start from the home screen.
3. Or open `game.html` directly to view the main game layout.

## Current Status

This version is mainly a UI prototype. It already includes:

- A title screen
- Navigation into the game screen
- Styled game board sections
- Card artwork and layout organization
- Hover effects for interactive elements

At the moment, the project does not yet include full JavaScript gameplay logic such as turns, attacks, scoring, or card interactions.

## Future Improvements ( mabye not )

- Add gameplay logic with JavaScript
- Connect buttons like `Start`, `Score`, and `Auto Play`
- Make the layout more responsive on smaller screens
- Add sound effects and animations
- Expand the card system with game rules

## Notes

- All assets are loaded locally from the `images` folder. no API
- The `scripts` folder exists, but the current version is primarily HTML and CSS based. ( it's there iffff i want to build the game )

## Author
me
