# The Handoff

A San Francisco sunset you scroll through. You stand on Treasure Island looking west: scroll down and the clock moves forward, the sun sets, the fog comes in through the Golden Gate, and the city's lights take over.

## What's real

- **The sun.** Its position, tonight's sunset time and the twilight times are calculated in the browser for San Francisco's current date (NOAA solar position algorithm).
- **Where it sets.** Landmarks are placed at their real compass bearings from Treasure Island, so the sun goes down behind whatever it actually goes down behind that day.
- **The lights.** Leo Villareal's Bay Lights on the Bay Bridge, the LED crown on Salesforce Tower, the red aviation lights on Sutro Tower and the bridge towers, and the Alcatraz light.

## What's stylized

Building and hill heights are stretched so the skyline reads at screen size. Clouds, fog and water are generated.

## Run it

It is a single `index.html` with no build step. Open it in a browser, or serve the folder with any static server. Fonts load from Google Fonts. It needs a browser with WebGL 2 and falls back to a still image without it. Motion is reduced when the system asks for reduced motion.
