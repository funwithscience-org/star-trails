# Two Disks, One Sky

Interactive page: **https://funwithscience.net/star-trails/**

A flat-earth demo gets counter-rotating star trails by projecting two spinning light disks onto one dome and filming from outside. The trick is real, but it is a camera trick. This page shows the trick, then the two things the "two disk" model cannot do: keep the disks from overlapping, and make the straight trails photographed at the equator.

## Tabs

1. **The dome trick** – 3D fisheye camera orbiting a dome with two projected star fields. From outside you see one field's back through the shell and the other's front across the dome, so they appear to counter-rotate although both disks spin the same way. Fly inside and both turn the same way. *Reverse disk B* grants the flat-earther's fix.
2. **Growing the fields** – All-sky view from underneath. Grow the radius and the fields overlap, with trails crossing through each other. The *Globe sky* preset (separation 180°, radius 90°, B reversed) is the only configuration that gives straight zenith trails, and it puts the second pole below the plane.
3. **Virtual Tenerife** – Panoramic star trails at 28.3° N, opening at the heading and span of the reference photo. Turn north (anticlockwise spiral), east (straight), south (opposite curvature). Switch to *Two disks*, one centred over each pole of the flat earth, and grow the radius.
4. **The mirror dome** – Reconstruction of the Hanvey tabletop from his two videos of 12 and 13 December 2024 (YouTube `Piub3NEOxUo`, `x3HEgGQL92E`): a clear acrylic dome over a printed map, a two-way mirror disk inside, and a lens-type star projector beside the dome, below its base, pointing up. The projector's cone paints one star field on the ceiling and never touches the dome; everything on the dome is that ceiling reflected: in the two-way mirror (about half the light, sharp, seen from above), in the acrylic's convex outer surface (about four per cent, soft when the phone is close), and a faint copy traced from the camera off the mirror and then off the inside of the cap (about one per cent, the picture turned over by the concave wall). From above the mirror that copy needs a third bounce and turns with the others; from below it (his close-ups) it is two bounces and turns the other way, which is the counter-rotation in Bright A. Optical flow on the raw frames fixes the senses: at 3:09–3:13 the near soft field turns −2°/s and the far sharp field +5°/s, against a straight-down mirror control of −7.8°/s. Each is solved per star by the law of reflection; the room has walls so the cone has somewhere to run off the ceiling, and a flat pane (the framed print's glass) can be stood beyond the dome to test what a picture reflection would do. The projector's shooting star is drawn in every copy and its direction on screen is measured, as is each copy's sense of turn. A storyboard walks his six shots in order, each with a short clip from the video playing beside the model set to the same view. Overlays are measured from the model, not drawn in: the seam arrows (each reflection fitted as a rotation on screen, evaluated at the mirror's rim), a camera-height gauge (above the mirror plane the mirror shows the ceiling, below it the map), his 6:44 crop (a 90° roll and 6× zoom on the seam) and a ghost of the lower half a fully starred dome would get from the mirror. The sliders can also aim the cone at the dome, in which case direct and mirror-bounced beam spots are traced and reported too.

Parked, unlinked from the page but still in `index.html`: *Personal spheres*, a Chicago/Washington two-observer demo answering the "personal observation sphere" argument (reachable by code only, `showTab('spheres')`).

## Engine

One model everywhere: each star field is a catalogue of stars in polar coordinates about its pole, rotated about that pole. Tab 1 views it with a 3D camera, tab 2 from directly underneath, tab 3 through a panoramic lens at a real latitude. The globe is the special case where the second pole is the first one's antipode, spinning the same way.

No build step, no dependencies beyond Google Fonts. `index.html` is the whole app.

## Credits

Reference photo: star trails over Teide Observatory, Tenerife, by J.C. Casado / IAC. Used here for comparison; all rights remain with the photographer.

`clips/` holds eight short excerpts (18–31 s, scaled to 854–960 px, no audio; clips 3 and 4 with brightness, contrast and gamma lifted, nothing cut inside them) and `ref/` eight stills from Joseph Hanvey's videos of 12 and 13 December 2024 (YouTube `Piub3NEOxUo` and `x3HEgGQL92E`), reproduced at reduced size for the purpose of identifying the apparatus under discussion and commenting on it. Rights remain with the author.
