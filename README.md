# НДК — National Palace of Culture, Sofia · interactive 3D model

A single self-contained HTML file (`index.html`) with an interactive, explodable 3D model of the
National Palace of Culture (НДК) in Sofia, built to scale from the architects' own plans. It has an
animated construction timeline running from the 1978 groundbreaking to the grand opening on
31 March 1981.

![Park view, aerial view, Hall 1 and the grand foyer](preview.jpg)

## Open it

Open `index.html` in a recent browser (Chrome, Edge, Firefox or Safari) on a desktop, tablet or
phone. The page needs WebGL 2 and an internet connection: Three.js (r160) loads from
`cdn.jsdelivr.net`, and fonts load from Google Fonts. There is no build step. All plan and map
data is embedded in the file.

## Where the geometry comes from

- **Floors 0–8.** Floor plates, walls, glazed partitions, stairs, escalators and columns are
  converted 1:1 from `NDK_Expo_Levels.dwg`, which NDK publishes on
  [ndk.bg › Планове на зали](https://www.ndk.bg/bg/planove-na-zali). The drawing is in centimetres;
  a 1 m exhibition grid confirms the scale. The ten level sheets are registered to each other by
  the structural columns that run through every floor, to within about 5 cm, and centred on the
  building's axis. Level 1's front mezzanine, drawn about 2.6 m out of place on its sheet, is moved
  onto the columns below and above it. The four lift and stair cores are drawn a little differently
  from sheet to sheet, and level 1 leaves them out. So all four are built from one drawing, the
  north-east core of level 5, reflected into the other three corners and repeated on every floor
  from level 0 to 8. The shafts run unbroken and are identical.
- **Levels −1 and −2.** The Azaryan Theatre and its entrance come from the `NDK Level −1/−2 Azaryan`
  PDFs on the same page.
- **Halls.** Positions, shapes and capacities follow the hall plans and pages on
  [ndk.bg › Зали](https://www.ndk.bg/bg/zali):
  - Hall 1: its seating plan.
  - Hall 3: its theatre configuration (four blocks and 322 lodge places).
  - Halls 7, 8, 9: 380 m² each, 7.15 m high.
  - Halls 3.1, 3.2, 3.4 and 10.
  - Halls 4 and 6, and Peroto.
- **Surroundings.** Bulgaria Square, the park, roads, tram tracks, fountains, trees and about 3,800
  buildings of central Sofia come from [OpenStreetMap](https://www.openstreetmap.org), projected
  into the building's frame. © OpenStreetMap contributors, ODbL.
  - The building's axis is 7.8° west of true north. It was found from the symmetry of the palace's
    OSM footprint, which also fixes where the palace sits on the map.
  - The underpass, the Cosmos fountain court and the metro are placed from the OSM layers −1 to −3.

The facades follow one mirror-symmetric line taken from the upper floors' outlines. The fins of
the diagonal fronts are read from the plans: each is a Y in plan, two 2 m arms opening outwards in
a V and a short stem inwards, repeating every 4 m along the diagonal with narrow glass between the
tips. The fins run unbroken from their foot to the cornice. On the outer wings the plans add a fin
or two per floor, so there the feet of the fins climb away from the towers. The heights between
floors are not in the published plans; they are reconstructed from photographs, the 7.15 m
ceilings of Halls 7–9 and the palace's overall height.

## What's inside

- **The real plan.**
  - A body about 116 m wide, with four white stair towers midway along the diagonal fronts. Each has
    a tall dark glazed slot and a copper roof that slants up into the crown.
  - The finned diagonal fronts, and the bronze-glass bay on the park side carrying Georgi
    Chapkanov's sun on a square white panel. The back has its own tall glass bay.
  - Roofs in three tiers, each set further in: the cornice of the level 7 terraces; level 8 under a
    deep eave and a copper mansard; and the crown over Hall 3, with a copper mansard and a low
    pyramid folded along an X and a + of ridges.
  - A long single-storey south block, containing Hall 6.
- **Every floor, as drawn.** Explode the model (button or slider) to pull apart the 13 levels, from
  −3 to the roof. Each floor shows its own walls, stairs and columns from the CAD plans. The
  facades move out with their floors. The square over the basements opens onto the excavation, so
  the underground levels show too.
- **Stairs in 3D.** The stair lines of the plans are read flight by flight and built as solid
  stairs:
  - The four cores share one imperial stair: a wide flight up to a landing, then two narrow flights
    back up on either side. It is the same on every floor, from level 0 to 8; only the risers
    change with the storey height.
  - The public stairs have red tile treads between solid dark-bronze parapets with stone caps,
    and climb to where the next floor continues.
  - In the atrium, flights that meet no floor get their own landings.
- **Halls on their real floors** (the Lumière cinema is left out: it is in a separate building
  south-west of the palace), with 6,585 seats placed individually. Every hall has a stage, and a
  screen showing its name, on the wall its seats face:

  | Hall | Where | Seats |
  | --- | --- | --- |
  | Hall 1 | levels 2–7 | 3,380: a fan-shaped parterre of 2,100 and two balconies, as in NDK's seating plan; 800 m² stage with a revolving disc |
  | Hall 3 | level 7 | 1,200: a stepped octagon, not a rectangle, with side lodges and a wide stair up from level 6 |
  | Halls 7, 8, 9 | level 5 | 260 each, facing a stage on the outer wall: triangular coffered ceilings with bulb chandeliers; Hall 8 faces its mural; Hall 9 has a balcony on level 6 |
  | Hall 10 | level 8 | 200 |
  | Halls 3.1, 3.2 | level 8 | 100 each |
  | Hall 3.4 | level 8 | meeting room |
  | Hall 4 | level 0 | 120 |
  | Hall 6 | level 0 | 200 |
  | Peroto | level 0 | 102 |
  | Hall 2 · Azaryan Theatre | level −2 | 403, around a round arena stage |

- **The sunken passage in front of the palace.**
  - An octagonal court, 31 × 32 m, opens in the square. The cascade pours into it, and at its
    bottom stands the Cosmos fountain of steel spheres.
  - A covered gallery rings the court.
  - The underpass runs east–west under the square. It has shops, stairs up at both sides and a
    passage north to the M2 station ‘NDK’.
  - On the south side, doors lead to the Azaryan Theatre foyer.
- **Grand foyer.** The gilded ‘Revival’ stands before a golden relief wall. Bronze-clad columns rise
  unbroken through the three-storey atrium. Three cascading bulb chandeliers hang in a row across
  the middle of the foyer. The two side ones hang from the ceiling of level 2; the large one in the
  centre hangs through the atrium's upper opening.
- **Build 1978 → 81.** A day-by-day animation:
  - The pit is excavated, tower cranes and trucks work the site, and floors are poured level by
    level.
  - The Hall 3 trusses are lifted in, and the marble and glass fronts close floor by floor.
  - Seats are installed and the park is planted, with fireworks at the opening.
  - Live counters track earth moved, concrete, steel and seats.
- **Views and tools.**
  - Realistic, white-maquette and x-ray styles.
  - A section cut.
  - Time of day from dawn to night, with lit windows, coloured fountains and stars.
  - A cinematic tour and camera presets.
  - Click any part for its facts. Selecting an underground part (level −1 to −3, Hall 2, the
    underpass or the metro) clears the building, the ground and the park away so you can see it.

## Controls

**Desktop.** Drag to orbit, right-drag to pan and scroll to zoom. Click a part, or pick it from the
list, to isolate it.

**Phones and tablets.** Drag with one finger to orbit, pinch to zoom and drag with two fingers to
pan. Tap any part for its facts, or tap empty sky to clear the selection.
- The **⚙** button opens the view controls and the **☰** button opens the list of parts.
- They open as bottom sheets in portrait and side drawers in landscape.
- The mode bar at the bottom switches between Explore, Explode and Build.
- Phones get a lighter rendering profile automatically. Add `?hq` to the URL to force full
  quality, or `?low` to force the light profile on a desktop.

Keyboard shortcuts:

| Key | Action |
| --- | --- |
| `E` | Explode |
| `B` | Build |
| `N` | Night |
| `M` | Maquette |
| `X` | X-ray |
| `F` | Fireworks |
| `R` | Reset the view |
| `Esc` | Clear the selection |

## Accuracy

- **1:1 from the sources:** the plan geometry of levels −2 to 8, hall positions and outlines, seat
  counts, the building's footprint and orientation, and the layout of the surroundings.
- **Reconstructed:** the heights between floors, the roofs, the finishes and the interiors of the
  halls. These follow photographs and are not measured drawings. The south half of the upper body
  is the north half mirrored, so from above it is a square with cut corners, as in aerial photos.
  The plans draw a recessed south front, which the model fills out to that line. The fins on the
  south fronts, which the plans do not draw, and the extent of the crown are reconstructed too.
- **Inferred:** which way each stair climbs, and its landings. The plans show where the flights and
  treads are but not their direction, so each flight climbs towards the side where the floor above
  (or its own floor, for flights in an opening) continues.
- **Level −3 is not published.** It is shown as a plant level on a structural grid.
