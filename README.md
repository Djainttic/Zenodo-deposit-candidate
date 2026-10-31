# Zenodo deposit candidate: OQE sub-THz MIMO antenna study

This folder is an **unpublished upload candidate** for the manuscript:

> Spline-profiled two-port sub-THz MIMO antenna with periodic dielectric perforation and defected-ground decoupling

Authors: Djalal Ziani-Kerarti and Fatima Zohra Marouf.

The deposit supports the simulation-only results reported in the manuscript. It contains the available two-port Touchstone export, the HFSS/CST S11 comparison spreadsheet, and the 22 manuscript figures in both PDF and EPS form. The source manuscript and bibliography are included under `optional_manuscript_source/` for reference; the Springer Nature `sn-jnl.cls` and bibliography style files are not included because they are supplied by the official Springer Nature/Overleaf template.

## Important status

This is a local candidate package only. It has **not** been uploaded or published to Zenodo. The existing concept DOI is:

<https://doi.org/10.5281/zenodo.22057365>

After uploading, create a new version of that record or use the appropriate Zenodo record selected by the authors. Replace the placeholder version DOI in the manuscript and journal submission materials with the exact DOI generated for the published version.

## Contents

- `supporting_data/MIMO_orthogonal90.s2p`: CST-generated two-port Touchstone export. The file header records the CST project context and parameter values available in the export. The data are stored in GHz, magnitude/angle format, with a 50-ohm Touchstone reference in the export.
- `supporting_data/hfss cst s11.xlsx`: workbook containing the available single-element and MIMO S11 comparison sheets.
- `figures_pdf/`: 22 PDF figures used in the manuscript.
- `figures_eps/`: EPS conversions of the 22 figures, named `Fig1.eps` through `Fig22.eps` for journal artwork workflows.
- `optional_manuscript_source/`: current OQE LaTeX source and BibTeX database for provenance and reference.
- `documentation/`: data dictionary, figure manifest, metadata draft, data-availability passage, deposit notes, and checksums.

## Scope and limitations

The supplied archive does not contain the original CST or ANSYS HFSS project files, complete solver model geometry, fabrication files, or every intermediate export used to create each plotted curve. The deposit therefore supports verification and reuse of the available exported data and figures but does not claim to be a complete reconstruction package. The manuscript identifies the results as numerical antenna-plane simulations requiring future experimental validation.

Before publication, the authors should verify the file contents, author metadata, funding information, repository license, version DOI, and any restrictions on redistribution of simulation exports.
