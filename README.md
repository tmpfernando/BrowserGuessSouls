⚔️ Souls Guess

"The fire is fading... Put the phone on your forehead and carry the burden of fallen realms!"

▶ Play now: BrowserGuessSouls

Souls Guess is a dark, immersive guessing game (inspired by Heads Up! / Charades) themed around the Souls-like universe. Gather your friends and find out who truly knows the bosses, weapons and unforgettable characters from the masterpieces of FromSoftware.

💀 About the Game

Built for mobile browsers, the game has a grim gothic look, classical typography (Cinzel), and a fully synthesized orchestral soundtrack generated in real time with the Web Audio API. There are no audio files, no images and no external assets to download.

Bonfire (menu): a calm, solemn theme with harp, soft choir and distant bells.
In-match music: two long, sinister tracks (roughly 1h45–2h10 of material before looping) with strings, solo violin, cello ostinato, brass, choir, timpani and tension risers. One is picked at random each match.
Iconic feedback: the screen banner shows ENEMY FELLED or VICTORY ACHIEVED when you score, escalating to GREAT ENEMY FELLED, HEIR OF FIRE DESTROYED, PREY SLAUGHTERED and LORD OF CINDER FALLEN on streaks. Skip a word and you get the classic YOU DIED.
🎮 Key Features
Realm-based categories: bosses, weapons and NPCs for each game, plus a mixed mode.
Multiple control modes (each can be toggled in the menu):
Tilt (gyroscope): tilt the phone down to score, up to skip.
Touch / Swipe: swipe down/up, or tap the word to score.
On-screen buttons: Triumph (got it) and Retreat (skip).
Responsive: works in both portrait and landscape on any smartphone.
Fullscreen mode and Screen Wake Lock so the display never sleeps mid-match.
Saved preferences: realm, trial duration and toggles are remembered via localStorage.
Chronicle of Souls: an end-of-match recap listing every word you felled or died on.
📜 Available Realms

Every game has three packs (Bosses, Weapons and NPCs), each with 25 to 40 entries that include DLC content:

Game	DLC included
Dark Souls	Artorias of the Abyss
Dark Souls II	Crown of the Sunken King, Crown of the Old Iron King, Crown of the Ivory King
Dark Souls III	Ashes of Ariandel, The Ringed City
Elden Ring	Shadow of the Erdtree

There is also a Mixed (All Realms) mode that combines every pack into one chaotic pool.

🚀 How to Play
Open the game in your smartphone's browser.
Place the phone on a player's forehead, screen facing the group.
Choose a Realm and a Trial Duration (30s, 1:00, 1:30 or 2:00).
Tap Light the Bonfire and wait for the countdown.
Your friends give hints without saying the word on the screen:
Triumph (correct): tilt the phone down, or tap / swipe down.
Retreat (skip): tilt the phone up, or swipe up.
When time runs out, review your results and pass the phone to the next Ashen One!
🛠️ Technologies Used
HTML5 / CSS3 / Vanilla JavaScript: a single file, lightweight and dependency-free.
Web Audio API: oscillator-based instruments (strings, brass, choir, harp, bells, timpani), a generated convolution reverb and a lookahead scheduler for the music and sound effects.
DeviceOrientation, Fullscreen and Wake Lock APIs for the in-hand experience.
Google Fonts: Cinzel and Rajdhani.
📦 Local Installation & Execution

The whole project is one standalone HTML file:

Clone or download this repository.
Make sure the main file is named index.html.
Open it in any modern browser, or serve it with a local server (e.g. VS Code Live Server).
To play with friends on mobile, host it for free on GitHub Pages or Netlify.

Note: tilt controls and audio require a user interaction first, and on iOS the browser asks permission for motion sensors. Motion sensors may also require HTTPS, which GitHub Pages and Netlify provide.

🛡️ License

Distributed under the MIT License. Feel free to modify, expand the lore and share it with the community of hunters and ashen ones!

Fan project. Dark Souls and Elden Ring are trademarks of FromSoftware / Bandai Namco. Not affiliated with or endorsed by them.
