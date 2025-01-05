# Production Files

Exported from the `.dwg` CAD files.

## Rail Slider Adapters

PCBWay and other sheet metal services can produce these. They should be 1.5mm stainless steel, the finish can be _as-machined_.

- `slider-adapter-right.iges` right-hand production file
- `slider-adapter-right-unfold.dwg` optional _unfolded_ right-hand side (for cutting the raw material before folding)
- `slider-adapter-right.pdf` optional PDF of right-hand side drawings and fold instructions
- `slider-adapter-left.iges` left-hand production file (mirror of the right)
- `slider-adapter-left-unfold.dwg` optional _unfolded_ left-hand side
- `slider-adapter-left.pdf` optional PDF of left-hand side drawings and fold instructions

The resulting parts take your choice of cage nut, either M5 or M6 (or UNF 10-32). The fronts need cage nuts in all three slots, the rears in two (top and bottom).

## 3D Printed Parts

- `slider-guide.step` to be glued into the adapters to accomodate the curve of the original outer rail; these allow manufacturing discrepancies to be tuned out, distributing the weight on the adapters as a whole and not just the screws
- `rack-guide.step` clips into the two small holes in each adapter allowing for easy insertion into the rack, also stopping any twisting as the cage nuts are tightened; sized here for SGI and IBM round holes
- `rack-guide-square.step` as above but for square holes
- `washer.step` custom washer for the rear inner rail screw to stop the mechanism from being fouled

## Optional 3D Printed Parts

- `drill-template-front.step`, `drill-template-middle.step` and `drill-template-back.step` templates to aide drilling the SGI mounting holes (clip into place and use a pin punch to mark the inner rail, follow with a centre punch, then a 5mm drill bit)
- `o350-saw-jig.step` jig to remove an excess 11mm when mounting the sliders on an Origin 350 (or any other machine in the CMN026 chassis); the longer Origin 300 is already the perfect size
- `o350-rail-filler.step` having removed 11mm, this part fills the end of the outer rail to stop the slider going too far
