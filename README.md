# My Weather

A small weather page built for one question: is today a good day to go out?

- Compares six forecast models (ECMWF, GFS, ICON, GEM, UKMO, Météo-France) and shows the median.
- Chance of rain comes from 80 ensemble runs (ECMWF + GFS).
- Scores each day against a personal taste: no rain, no grey skies, no humid heat, no strong wind.
- Live rain radar from RainViewer.

Data: [Open-Meteo](https://open-meteo.com) and [RainViewer](https://www.rainviewer.com). No API keys, no build step: open `index.html`.
