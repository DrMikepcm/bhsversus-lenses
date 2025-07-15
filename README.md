# Black Hole Clustering Near Strong Gravitational Lenses

This project investigates whether black hole–associated astrophysical objects 
(e.g., AGNs, QSOs, BL Lacs) cluster significantly near strong gravitational lenses.

Using data from the `lenscat` catalog and SIMBAD queries within various angular radii, 
we compare 200 known lens positions against randomly generated control points 
that are filtered to avoid all known lenses.

### Features

- Queries SIMBAD for AGN/QSO/BLLac objects
- Avoids overlap with known lens systems in random control generation
- Runs Poisson and KS tests on object counts
- Outputs summary statistics per radius (10′, 15′, 20′)

### Requirements

To run the script, install the following Python packages:

```bash
pip install numpy pandas astropy scipy astroquery lenscat
# bhsversus-lenses
