# Mymuna Sultana · portfolio

Live: **https://smymuna.github.io/portfolio/**

An interactive portfolio where every demo runs on real data from my own projects:

- **Career journey**: a globe that flies through my education and work, from Warangal to George Mason University to what's next.
- **OrbitWatch**: 19,375 real objects in orbit, propagated with SGP4 in the browser (Web Worker), including a replay of the closest predicted approach (11 m).
- **GridShift**: drag a job window across the day's grid carbon intensity for 8 European countries and find the cleanest time and place.
- **Climate Emissions Platform**: greenhouse gas emissions for 30 countries, 1990–2024, in total or by sector.

Plain HTML, CSS and JavaScript, no build step. Data snapshots in `data/` come from the
[OrbitWatch](https://github.com/smymuna/orbitwatch) release of 8 Oct 2026, Energy-Charts
(Fraunhofer ISE) on 9 Oct 2026, and Eurostat via the
[Climate Emissions Platform](https://github.com/smymuna/climate-emissions-platform)'s own adapter.

Run locally: `python3 -m http.server` in this folder, then open http://localhost:8000.
