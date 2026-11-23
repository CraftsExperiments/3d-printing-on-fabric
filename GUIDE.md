# Guide to 3D Printing on Fabric

You can combine 3D printed shapes with fabric to make flexible bookmarks. This guide describes the pause-and-insert method: print a thin base, pause, place fabric over it, then continue printing to trap the fabric between layers of plastic.

These are starting instructions for experiments. You can always test a small sample before printing a full project.

## What You Need

- An FDM 3D printer with a reliable pause-and-resume function.
- A slicer that supports inserting a pause at a chosen layer.
- An STL model designed for printing on fabric, with plastic below and above the fabric insertion point.
- Thin, open mesh fabric, such as tulle, for a first test. Openings let the upper and lower plastic layers connect around the threads.
- Filament suitable for your printer. PLA is a simple starting option for rigid shapes; TPU can make flexible shapes but needs its own print profile.
- Small magnets (6-10mm diameter) as a way to secure the fabric, or heat-resistant tape compatible with your build surface.

## 1. Prepare Materials

Start with a small, flat shape or a small part of your project. Use a scrap of your chosen fabric (please use tulle as the first sample) to check that it tolerates the printing conditions and bonds well with the plastic. Thick, tightly woven, coated, or stretchy fabrics should be avoided and have not worked in any of my experiments.

Cut the fabric large enough to cover the design and leave room to secure its edges. I typically leave one inch in all directions, you can leave less. Keep loose threads and excess fabric away from the printer's moving parts. 

## 2. Prepare the Model in Your Slicer

1. Import the model from its folder under `models/`.
2. Choose your usual working printer and filament profile. Follow the filament maker's temperature guidance.
3. For a first sample with a 0.4 mm nozzle, a 0.2 mm layer height is a reasonable experiment; use project-specific settings when available.
4. Insert a pause after a thin plastic base has printed, before the next layer begins. Two base layers can be a starting test if the model has enough layers above them to hold the fabric. You can experiment with how many layers you want to keep before and after fabric insertion. Different thickness creates different effects.
5. Inspect the layer preview. Confirm that plastic will print on both sides of the fabric and that separate decorative pieces will remain connected by the fabric.

Use the pause feature supported by your specific printer and slicer. Verify visually that it parks the print head and resumes correctly before attempting fabric insertion. Layer numbering varies between slicers, so verify the pause position in the preview rather than relying only on a layer number. 

## 3. Print the Base

Clean and prepare the build plate as you normally would for the chosen filament. Start the print without fabric on the bed and watch the first layers. A flat, well-attached base makes the next step easier.

Wait for the planned pause and for the print head to park before placing the fabric.

## 4. Add the Fabric

1. Leave the printed base attached to the bed. Avoid moving the build plate or printer axes.
2. Lay the fabric over the base, smooth and flat, without folds. For your first test, avoid stretching it deliberately.
3. Secure the edges outside the printing area. Keep tape and any fasteners clear of the nozzle, probe, fan shroud, and the FULL TRAVEL PATH of the bed and print head.
4. Check that loose fabric cannot catch on belts, fans, or other moving parts. Account for the air flow - fabric will move if it is not secured with the magnets. 

Attention: The nozzle, bed, and printed plastic may still be hot. Keep your hands clear of hot parts. If you use clips or magnets instead of tape, check clearance carefully; being outside the model outline does not necessarily put them outside the printer's travel path.

## 5. Resume Printing

Resume using the printer's normal controls and watch the first layers over the fabric. Plastic should pass through the mesh and connect to the base underneath.

If the nozzle drags the fabric, the fabric bunches up, or the base lifts, stop the print and adjust the setup before trying again. Fabric adds thickness: if clearance is insufficient, try a thinner fabric or consult your printer's guidance for handling inserts. 

## 6. Remove and Finish

Let the bed and print cool, then release the project gently according to your build plate's instructions. Remove tape or magnets and trim excess fabric, leaving the border you want. Avoid cutting the threads that hold separate printed pieces together.


## Troubleshooting

| Problem | What to try |
| --- | --- |
| Fabric moves or wrinkles | Smooth it again and secure the edges more evenly. Check for loose fabric catching on moving parts. |
| Plastic peels away from the fabric | Try a more open mesh and check that the model has overlapping plastic layers below and above the fabric. Test one change at a time. |
| Nozzle catches the fabric | Stop the print. Check for folds, loose threads, raised fasteners, or fabric that is too thick for the setup. |
| Base comes off the bed | Improve normal first-layer adhesion and avoid pulling on the base while positioning fabric. |
| Fabric melts, shrinks, or discolors | Stop the test and choose a different fabric or a compatible printing setup. Do not keep increasing heat to improve attachment. |
| Project is too stiff | Try smaller printed islands with fabric gaps between them, or test a flexible filament with a suitable profile. |

## Watch Video

For an example of the pause, insert, and resume workflow in practice, see this [3d printing on fabric video](https://www.instagram.com/reel/Ddwv4ouTIS6/). Adapt the method to your own equipment rather than copying another printer's pause commands.

[Back to the project list](README.md)
