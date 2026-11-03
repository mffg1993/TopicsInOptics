# Polarization of Light: Interactive Jones and Stokes Polarimetry Tutorial

An interactive, notebook-based introduction to the description, manipulation, and measurement of optical polarization. The material is intended for undergraduate and graduate students learning polarization optics and experimental polarimetry.

The tutorial combines short theoretical explanations, Jones and Stokes calculations, interactive visualizations, and checkpoints. It concludes with a virtual laboratory in which students measure an **unknown polarization state** using simulated waveplates, a polarizing beam splitter (PBS), and a single detector.

## Open the tutorial

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mffg1993/TopicsInOptics/blob/main/Polarization/InteractiveStokesPolarimetryLAB.ipynb)

- **Interactive notebook:** [View on GitHub](InteractiveStokesPolarimetryLAB.ipynb) or use the **Open in Colab** button above to run the experiments.
- **Printable PDF:** To be added after the notebook is exported. The PDF will be a reading copy; interactive sliders and measurements require the notebook.

## What you will learn

| Topic | Activities |
| --- | --- |
| Polarization ellipse | Explore linear, circular, and elliptical polarization by changing amplitudes and relative phase. |
| Jones calculus | Represent optical elements with matrices and investigate how waveplates transform a polarization state. |
| Stokes parameters and Poincaré sphere | Relate polarization states to measurable quantities and visualize them geometrically. |
| Waveplate transformations | Rotate individual QWPs and HWPs, then combine QWP–HWP–QWP elements into a polarization controller. |
| Stokes polarimetry | Reconstruct the Stokes vector from six intensity measurements and investigate a single-detector analyzer. |
| Virtual laboratory | Rotate a HWP and QWP, record detector readings for a randomized unknown state, and calculate its polarization by hand. |

The notebook also includes conceptual checkpoints and discussion of practical laboratory considerations, such as waveplate calibration, alignment, and measurement uncertainty.

## Running the experiments

1. Click **Open in Colab** above, or download the notebook and open it with JupyterLab.
2. Run the setup cells at the beginning of the notebook before using the interactive experiments. In Colab, **Runtime → Run all** is a convenient way to initialize the notebook.
3. Use the dropdown menus and sliders to explore the examples. Answer the checkpoint questions as you progress.
4. For the virtual laboratory, record the six analyzer intensities and calculate the Stokes parameters **before** revealing the reference answer.

The notebook uses **NumPy**, **Matplotlib**, **ipywidgets**, and **IPython**. Google Colab provides a browser-based Python environment, so no local Python installation is necessary.

> **Important:** GitHub previews of notebooks are static. To move the sliders and run the virtual laboratory, open the notebook in Colab or Jupyter.

## Printable version

A PDF reading copy can be placed in this folder as `Polarization_Tutorial.pdf` once exported from the notebook. It is intended for reading, annotation, and printing; the notebook remains the primary interactive version.

<!-- After uploading the PDF, replace the paragraph above with:
[Read or download the printable PDF](Polarization_Tutorial.pdf)
-->

## References and conventions

The tutorial builds on standard Jones and Stokes formalisms. Primary and further references are listed within the notebook, including Gutiérrez-Vega's polarization lecture notes, *Polarized Light and Optical Systems* (Chipman, Lam, and Young), and *Introduction to Modern Optics* (Fowles).

Circular polarization and retardance conventions vary between textbooks. The notebook defines its conventions explicitly; use these when comparing formulas and experimental settings.

## Feedback and reuse

Suggestions and corrections are welcome through the [repository issues](https://github.com/mffg1993/TopicsInOptics/issues). See the [repository license](../LICENSE) for reuse terms.

**Author:** Manuel Ferrer-Garcia
