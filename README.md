# Corner Office test build

A corporate and life sim set in a fictional American city. This is a playtest build that runs in the browser with nothing to install.

## Play

Open `index.html` in a browser. With GitHub Pages switched on for this repository, the game plays at the Pages address for the repo.

The game opens on a main menu. Continue or start a new game from there, or open the engine sandbox or any of the component tests.

`engine.html` is the street engine on its own, with buttons for time of day, weather, season and sound, for checking how the city looks and sounds.

## What is in this build

- The full generated city, with traffic, pedestrians, pigeons, food carts, police and day and night
- The share house with Rob, the Meridian Capital office in Northgate tower, and venues to visit
- Lit doors on every place you can enter, which are also where you come back out
- Portraits from the Portrait Creator, and hand-made portraits for Rob and Topher
- Muted horn voices in conversations, the city soundscape and one radio station
- Work shifts with promotions, needs, money, sleep and saving. Work, study, TV and sleep run the clock fast while you stay in the room
- Conversations that follow a thread, with numbers to swap and coffee to arrange
- A phone with contacts, messages, bank, maps, calendar, music and a journal. Time stops while it is open
- A stereo in the share house, and cars going past with their music up
- Halloween ghosts, December lights and New Year's Eve on their dates

## Controls

- WASD or arrow keys to move, Shift to run
- E to use, enter, talk or get in and out of the car
- R for the radio while driving, Shift and R to skip a song
- P for your phone
- Space to skip ahead while time is running fast
- M for the map, Q and Z to turn the view, N to face north
- Mouse wheel, or plus and minus, to zoom
- Esc for the menu, saves and sound settings

## Files

- `index.html` is the game
- `engine.html` is the engine test page
- `portraits.js` holds the portrait art, loaded after the city starts
- `music` holds the songs for the radio and venues
- `tests` holds every standalone component test, each a single page that opens from the main menu

Saves are kept in the browser on the device you play on.
