# BLAST Explorer

BLAST Explorer is a graphical parsing and analysis tool designed to aid in the tracking of PSI-BLAST results across iterations. It turns multi-iteration PSI-BLAST output into linked visual modules for analysis of local alignment data across iterations by identity, taxonomy, annotation, and statistical criteria. The integrated alignment viewer enables sequence-level investigation of high-scoring segment pairs (HSPs) across matched subjects and iterations.

## Installation

1. On GitHub, select the *Code* dropdown and select *Download ZIP*.
2. Extract the zipped files.
3. Open the [BLAST_Explorer.html](BLAST_Explorer.html) file in a local browser such as Chrome.

## Run test

1. Navigate to *Session → Load a previous session* and press *Choose File*.
2. Navigate to `vignettes/vignette_1_quick_start/vignette1/` in the extracted folder.
3. Select *P0CU51.1_metadata.psiv* and press *Open*.
4. Scroll down and confirm the presence of data in the *Analysis modules* and *Alignment workspace*.

The same folder contains `P0CU51.1_raw.psiv` for the example without metadata, plus the three XML2 and three Saved Search Strategy files for a fresh import.

## Load and analyze your own PSI-BLAST run results

1. Obtain a *Single-file XML2* alignment file and a *Saved Search Strategy* for each iteration.
2. Navigate to *Session → New session* and select the files for all iterations together. Scroll down to the *Analysis modules* and *Alignment workspace* to view your results.
3. To add metadata, open *Metadata*, select *Query*, *Subject GenPept*, or *Taxonomy* as needed, and click *Fetch Metadata*. If you select *Query* and its accession is blank, enter it before fetching.

See [User Guide page 2](documents/BLAST_Explorer_User_Guide.pdf#page=2) for instructions on obtaining the input files and adding metadata from local files.

## Documentation

- [User Guide](documents/BLAST_Explorer_User_Guide.pdf)
- [Vignette 1](vignettes/Vignette_1.pdf)
- [Scientific Colour Maps license](licenses/Scientific-Colour-Maps-LICENSE.txt)
