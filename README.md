# plate-saturator
Companion page for the paper *Efficient Simulation of Acoustic Physical Models with Nonlinear Dissipation*.

This repository stores audio samples obtained with the algorithms described into the paper, and higher-resolution images.

`images` contains a higher-res version of most images present in the paper.

`dry_samples` contains non-reverbed audio samples.

`wet_samples` has two subfolders: `Test` contains audio samples obtained with a small plate of $0.4 \times 0.6$ meters, and with constant damping. `physicalDamp` stores the output samples of a bigger, $1 \times 2$ meters plate, with a physical model for damping. Note that each file has information on the input gain (amp), the values of $c$ and $a$ and the nonlinearity used.

