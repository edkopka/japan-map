# Japan Map

An interactive map for learning Japan's 47 prefectures, with Japanese and English names and three quiz modes.

Open [index.html](index.html) in a modern browser to start.
The page includes all HTML, CSS, JavaScript, SVG, and prefecture data in one file, so it works offline without installation, a build step, or a server.

Choose a mode using the buttons above the map:

- **Explore:** Click a prefecture to highlight it and see its Japanese and English names.
- **Find on Map:** Click the prefecture named in the prompt. Each game has 10 randomly selected prefectures and three guesses per round. Incorrect selections turn red, correct selections turn green, and the answer is revealed in amber when guesses run out.
- **Name All:** Type the English names of as many prefectures as you can, pressing Enter after each name. Found prefectures turn green. Find all 47 or select **Finish game** to see your score and the prefectures you missed. Click a missed name or a prefecture on the map to review its location and names.
- **Name Highlighted:** Type the English name of the blue highlighted prefecture and press Enter. Each game has 10 randomly selected prefectures and three guesses per round. Use **Skip**, or enter `skip` or `I don't know`, to reveal the answer and move on using **Next round**.

English name matching ignores capitalisation and surrounding spaces.
Find on Map and Name Highlighted show a final score and a breakdown of each round's guesses.
Switching modes starts a fresh session; progress is not saved after reloading.

Hold Ctrl or Command while scrolling over the map to zoom between 1× and 4×.
Scroll within the map panel to move around when zoomed in.

The SVG map and prefecture data come from [Geolonia's japanese-prefectures repository](https://github.com/geolonia/japanese-prefectures).
This page embeds its `map-full.svg` map, which is based on Wikipedia's Japanese map SVG and licensed under the GNU Free Documentation License (GFDL), as documented in the source repository.
