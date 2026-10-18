# Two Disks, One Sky

Interactive page: **https://funwithscience.net/star-trails/**

A flat-earth demo gets counter-rotating star trails by projecting two spinning light disks onto one dome and filming from outside. The trick is real, but it is a camera trick. This page shows the trick, then the two things the "two disk" model cannot do: keep the disks from overlapping, and make the straight trails photographed at the equator.

## Tabs

1. **The dome trick** – 3D fisheye camera orbiting a dome with two projected star fields. From outside you see one field's back through the shell and the other's front across the dome, so they appear to counter-rotate although both disks spin the same way. Fly inside and both turn the same way. *Reverse disk B* grants the flat-earther's fix.
2. **Growing the fields** – All-sky view from underneath. Grow the radius and the fields overlap, with trails crossing through each other. The *Globe sky* preset (separation 180°, radius 90°, B reversed) is the only configuration that gives straight zenith trails, and it puts the second pole below the plane.
3. **Virtual Tenerife** – Panoramic star trails at 28.3° N, opening at the heading and span of the reference photo. Turn north (anticlockwise spiral), east (straight), south (opposite curvature). Switch to *Two disks*, one centred over each pole of the flat earth, and grow the radius.
4. **The mirror dome** – Reconstruction of the Hanvey tabletop from his lit-room shots (13 Dec 2024 video): a clear acrylic dome over a printed map, a horizontal two-way mirror disk mounted near the top inside, a pinhole star projector on a box outside. Every beam is traced: glass entry and exit, mirror reflection and transmission, ceiling, map. The dome carries a direct copy of the field and a mirrored (reversed) copy, plus hot spots on the map and the ceiling seen reflected in the mirror. Mirror height and radius and projector position are sliders; switch the mirror off and every reversed component vanishes. Swept-area readouts give each copy's on-screen sense. Presets reproduce his tripod shot, his long exposure, the view from above and the view from inside under the mirror.

Parked, unlinked from the page but still in `index.html`: *Personal spheres*, a Chicago/Washington two-observer demo answering the "personal observation sphere" argument (reachable by code only, `showTab('spheres')`).

## Engine

One model everywhere: each star field is a catalogue of stars in polar coordinates about its pole, rotated about that pole. Tab 1 views it with a 3D camera, tab 2 from directly underneath, tab 3 through a panoramic lens at a real latitude. The globe is the special case where the second pole is the first one's antipode, spinning the same way.

No build step, no dependencies beyond Google Fonts. `index.html` is the whole app.

## Credits

Reference photo: star trails over Teide Observatory, Tenerife, by J.C. Casado / IAC. Used here for comparison; all rights remain with the photographer.

`ref/` holds six stills from Joseph Hanvey's videos of 12 and 13 December 2024 (YouTube `Piub3NEOxUo` and `x3HEgGQL92E`), reproduced at reduced size for the purpose of identifying the apparatus under discussion and commenting on it. Rights remain with the author.
