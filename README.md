How to view the interactive Brooklyn films map

1) Easiest:
   - Open brooklyn_films_map.html in a modern browser.

2) If markers don't load (some browsers block network requests when opening a file directly):
   - In the folder containing the HTML file, run:
       python3 -m http.server 8000
   - Then open in your browser:
       http://localhost:8000/brooklyn_films_map.html

Controls
- Hover a marker: tooltip with film title/year
- Click a marker: popup with details
- Sidebar: search films + click a film to zoom to its markers
- Toggles: show/hide feature films and shorts/actualities layers
