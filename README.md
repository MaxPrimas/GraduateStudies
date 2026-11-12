# Interactive Physics Demos

Browser-based simulations of topics from my physics coursework. Each one is a single web page: open it, change the parameters, and watch the physics respond.

**Live site: https://maxprimas.github.io/GraduateStudies/**

## Demos

| Demo | Topic | What it shows |
| --- | --- | --- |
| [Aperture Wavefront Lab 3D](https://maxprimas.github.io/GraduateStudies/aperture-wavefront-lab-3d.html) | Optics | A spherical wave diffracting through an aperture of any shape onto a screen, in 3D |
| [Aperture Wavefront Lab](https://maxprimas.github.io/GraduateStudies/aperture-wavefront-lab-2d.html) | Optics | The slit version: single slit, double slit, straight edge, grating, curved and tilted apertures |
| [1D Ising Chain](https://maxprimas.github.io/GraduateStudies/ising-chain-1d.html) | Statistical mechanics | A Monte Carlo spin chain compared live with the exact transfer-matrix results |
| [Landau Theory of Phase Transitions](https://maxprimas.github.io/GraduateStudies/landau-phase-transitions.html) | Statistical mechanics | Continuous and first-order transitions, metastability, and the tricritical point |
| [Bloch Sphere](https://maxprimas.github.io/GraduateStudies/bloch-sphere.html) | Quantum mechanics | Spin-½ precession in a magnetic field, with the density matrix updating live |
| [H₂ Molecular Orbitals](https://maxprimas.github.io/GraduateStudies/h2-molecular-orbitals.html) | Quantum mechanics | Bonding and antibonding orbitals and the energy curve that makes a chemical bond |

## How the site works

- `index.html` is the homepage: a gallery with one card per demo.
- Every other `.html` file is one self-contained demo (page, styling and simulation code in a single file).
- GitHub Pages serves the files from the `main` branch. Changes go live a minute or two after a commit.

## Adding a demo

1. Upload the new `.html` file to the top level of this repository.
2. Open `index.html`, copy an existing card (from `<a class="card" ...>` to `</a>`), and paste it into the section it belongs to.
3. Change the card's `href` to the new file name and edit its title, description and tags.
4. Add a row to the table above.

## Running a demo offline

Download the file and double-click it. Everything runs in the browser with no installation. The 3D wavefront lab needs an internet connection, because it loads the three.js library from the web.

## Credits

Built with plain HTML, CSS and JavaScript, developed with help from Claude (Anthropic).
