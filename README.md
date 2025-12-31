# Epstein Flights Map

A web application visualizing publicly available flight and passenger data.
Built for **research, educational, and journalistic purposes only**.

## License & Disclaimer

This entire project (code, data, and visualizations) is licensed under **[Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)**.

- You may **share and adapt** the project, but **not for commercial purposes**.
- Proper **attribution is required** when using or redistributing the material.
- The creators of this project **do not claim ownership** of the underlying data.
- Accuracy of the data is **not guaranteed**. Use at your own discretion and risk.
- Again, this project is intended for **research, education, and journalism** only. Do **not** use to harass or target individuals.

## Usage

Open https://dchacke.github.io/epstein-flight-map/ to see the map.

The map shows airports and flights, with filtering options for dates, airports, and passengers. Clicking a route displays details in the offcanvas panel.

## Contributions

Contributions to improve visualization, usability, or documentation are welcome. Run a web server, then open `index.html` in a modern browser.

## Credit

I vibe coded this project using Grok and ChatGPT.

Data is sourced from https://ia801606.us.archive.org/30/items/epstein-flight-logs-unredacted_202304/EPSTEIN%20FLIGHT%20LOGS%20UNREDACTED.pdf

I then normalized the data. It looks like it’s the result of optical character recognition, so it contains some mistakes. I corrected wrong names and airport codes by hand. Diff epstein_flights.json and epstein_flights_normalized.json to see the changes I made.
