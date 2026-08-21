# CarND Term 1 — Lane Line Detection

An archived Udacity Self-Driving Car Nanodegree exercise exploring classical computer-vision techniques for detecting road lane lines with Python and OpenCV.

## What is in this repository

The original work lives in [`CarND/`](CarND/):

- `P1.ipynb` and `P1_Edited.ipynb` — project iterations
- `Lane Finding Algorithm from Image - Vertigo.ipynb` — an extended experiment
- Step-by-step notebooks covering colour selection, region masking, Canny edges and the Hough transform
- Sample images and other project assets used by the notebooks

The project follows the familiar classical pipeline: colour filtering → region of interest → edge detection → Hough line detection → lane overlay.

## Getting started today

The notebooks were created in 2017, so the original Udacity starter environment is no longer a reliable installation target. A modern local setup is straightforward:

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
python -m pip install --upgrade pip
pip install jupyterlab numpy matplotlib opencv-python moviepy
jupyter lab
```

Open one of the notebooks under `CarND/` and run it interactively. Because these are historical notebooks, dependency or API changes may require small compatibility fixes on newer Python releases.

### Dependency maintenance

This archived repository does not maintain a locked historical environment. Install current, supported releases of the packages above rather than reviving the original 2017 package stack. If a future compatibility fix requires pinning a package, the pin should be documented here and kept as narrow as possible; deprecated or unmaintained packages should not be reintroduced merely to reproduce the old coursework environment.

## Update policy

This repository is primarily an archived learning project, so it does not update itself or modify your environment automatically. To safely obtain the latest maintained copy:

```bash
git pull --ff-only origin master
```

`--ff-only` prevents Git from creating an unexpected merge commit. To stay on a known revision, check out a specific tag or commit instead:

```bash
git fetch --tags
git checkout <tag-or-commit>
```

If future runnable releases are published, use the corresponding GitHub Release tag as the reproducible version to install or check out.

## Versioning and releases

Repository maintenance follows Semantic Versioning:

- **MAJOR** — incompatible restructuring or changes to the documented project layout
- **MINOR** — new documented learning material or compatible runnable additions
- **PATCH** — documentation, dependency guidance, or compatibility fixes

See [CHANGELOG.md](CHANGELOG.md) for release notes.

## Status

The original lane-detection notebooks are preserved as the implementation. The current maintenance goal is reproducibility and documentation rather than rewriting the historical coursework into a new application.

## Original project material

The original Udacity project instructions remain in [`CarND/README.md`](CarND/README.md). Some of its external links and setup instructions reflect the 2017 course environment and should be treated as historical references.
