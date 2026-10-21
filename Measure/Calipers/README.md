# PlaStim Caliper v1.1

A printed soft-tissue caliper. The moving jaw has a built-in touch indicator: a small flexure that shows when you are
pressing with the same light force (about 1 N) every time, so readings don't depend on how hard you squeeze.

Licence: CC BY-NC 4.0, attribute PlaStim.

## Folders

- `two-color/`: each part is one STEP with two bodies (the part + a 1.0 mm top layer), for a two-color print. In Bambu
  Studio the two parts only show when the Process row is switched from Global to Objects.
- `one-color/`: single solids with the same marks cut 1.4 mm deep, for a single-color printer.

## Print list

PLA, 0.4 mm nozzle, 0.20 mm layers, no supports, every part flat as modelled. Use two strongly contrasting colors.

| File | Qty | Approx. time | PLA | Size (mm) |
|---|---|---|---|---|
| `caliper-v1.1-scale-sample.step` (optional: check your colors first) | 1 | 6 min | 2.6 g | 44 x 18 x 5 |
| `caliper-v1.1-carriage.step` (fits all three beams) | 1 | 24 min | 10.7 g | 71 x 67.5 x 8 |
| `caliper-v1.1-beam-compact.step` (0-56 mm) | 1 | 23 min | 10.0 g | 149.6 x 60 x 8 |
| `caliper-v1.1-beam-standard.step` (0-88 mm) | 1 | 28 min | 11.9 g | 181.6 x 60 x 8 |
| `caliper-v1.1-beam-length.step` (8-190 mm) | 1 | 42 min | 16.8 g | 274.6 x 30 x 14 |

The length beam is 274.6 mm long: flat on a 330 x 320 bed, or corner to corner on a 256 x 256 bed.

Assemble: slide the carriage onto a beam from the free end, jaws on the same side. There is no end stop; the carriage
comes off the same way.

## Reading

- One row of blocks: 1 mm of mark, 1 mm of gap. Every block edge is a whole millimetre; the block at every 10 is longer
  and its number hangs under it.
- The pointer is one straight edge in the plane of the moving jaw's face. On a block edge = a whole millimetre; halfway
  along a block or a gap = the half.
- Touch: close with your thumb on the ribbed straps until the line on the carriage's finger meets the nick and the line
  on the jaw's base. That is 1.0 mm of flexure travel, about 1 N. Read the scale there.
- "Place here": the line across both jaws 20 mm out from the beam. Put what you measure on that line each time.
- Card check: close on a bank card (85.60 x 53.98 mm). The pointer should cut the diamond in half: the long side on the
  standard and length beams, the short side on the compact beam.
- Length beam: lay it along the top, press the landing pad back against the pubic bone, bring the jaw down across the
  tip until the touch lines meet, and read. It reads from the pad's outer face.
