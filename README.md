# НДК — National Palace of Culture, Sofia · interactive 3D model

A single self-contained HTML file (`index.html`) with an interactive, explodable 3D model of the
National Palace of Culture (НДК) in Sofia. It has an animated construction timeline running from
the 1978 groundbreaking to the grand opening on 31 March 1981.

![Park view, aerial view, Hall 1 and the grand foyer](preview.jpg)

## Open it

Open `index.html` in a recent browser (Chrome, Edge, Firefox or Safari) on a desktop, tablet or
phone. The page needs WebGL 2 and an internet connection: Three.js (r160) loads from `cdn.jsdelivr.net`, and
fonts load from Google Fonts. There is no build step. Everything else, including geometry,
textures, landscape and animation, is generated procedurally in the file.

## What's inside

- **Exterior**, modelled from photographs of the building:
  - four wings of white marble fins and dark bronze glass;
  - the north bay with Georgi Chapkanov's bronze sun on its white panel;
  - diagonal corner arms and towers under green copper roofs;
  - stepped crowns and roof terraces;
  - a low copper pyramid over the central hall;
  - a terraced podium, the octagonal fountain and the park cascade;
  - Vitosha mountain behind.
- **Explode** (button or slider) separates the 12 levels, the fronts, towers and crown, so you can
  see every floor plate, hall and core.
- **Halls with individually placed seats**, 6,754 in total:
  - Hall 1: 3,380 seats. Orange seats on royal-blue carpet, golden balcony fronts, an LED stage wall.
  - Hall 3: 1,200 seats, on floor 7.
  - Hall 2, the Azaryan Theatre: 504 seats.
  - Hall 11, the Lumière cinema: 370 seats. It plays a looping homage to the Lumière train film.
  - Halls 4, 6, 7, 8, 9 and 10.
- **Grand foyer**:
  - white marble floor;
  - triangular coffered ceilings with lights at the nodes;
  - bronze gallery bands around the atrium;
  - cascading bulb chandeliers;
  - the gilded 'Revival' figure before a golden relief wall.
- **Underground**: three levels, including a garage for more than 1,000 cars and the ‘NDK’ metro
  station.
- **Build 1978 → 81**: a day-by-day animation.
  - The pit is excavated, tower cranes and trucks work the site, columns rise floor by floor, steel
    trusses are lifted in and the facades are clad.
  - Seats are installed, the park is planted, and fireworks mark the opening.
  - Live counters track earth moved, concrete, steel and seats.
- **Views and tools**:
  - realistic, white-maquette and x-ray styles;
  - a section cut;
  - time of day from dawn to night, with lit windows, coloured fountains and stars;
  - a cinematic tour;
  - camera presets;
  - click any part for its facts.

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

These come from public sources (Wikipedia EN/BG, ndk.bg):

- hall capacities and areas;
- the 51 m height;
- 123,000 m² of floor area;
- construction dates: first column 20 Jul 1979, last column 25 Mar 1980, opening 31 Mar 1981;
- quantities: 1.7 Mt of earth, 335,000 m³ of concrete, about 10,000 t of steel;
- the artworks.

The exterior massing and materials follow the photographs. The interior layout, meaning where each
hall and room sits on its floor, is an artistic reconstruction.
