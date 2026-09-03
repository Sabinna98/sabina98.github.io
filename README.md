# Minoan Motif Reception

## The Reception of Minoan Motifs in Modern and Contemporary Textiles and Fashion: Digital Analysis through Computational Image Clustering

A non-commercial research dataset developed as part of a Master’s thesis in Digital and Public Humanities at Ca’ Foscari University of Venice.

The repository contains the image corpus, metadata, and computational outputs used to investigate the reception of Minoan and Aegean Bronze Age motifs in modern textiles, stage costume, and fashion.

**Interactive visualisation:**  
[Open the published PixPlot environment](https://sabinna98.github.io/sabina98.github.io/index.html)

---

## Dataset

The final computational corpus contains **180 motif crops** organised through three historical layers:

- **Archaeological** — Minoan and Aegean Bronze Age objects and frescoes;
- **Publication** — images from archaeological books, plates, and other publications;
- **Reception** — modern and contemporary textiles, costume, and fashion.

The corpus contains **5 broad motif groups** and **23 specific motif terms**.

Each motif crop remains connected to its parent image and to descriptive information concerning its source, object type, chronology, corpus layer, motif classification, author or designer where applicable, and institutional or bibliographic reference.

The crop is used as the computational unit because it allows individual motifs to be compared without the visual complexity of the complete object or publication page.

---

## Method

The workflow combines manual corpus construction with computational image analysis:

1. selection and documentation of relevant source images;
2. extraction of individual motifs from parent images;
3. construction of structured metadata;
4. computational visualisation with PixPlot;
5. comparison of visual proximity with motif classifications, provenance, publications, and close visual analysis.

The project follows a human-in-the-loop approach. Computational methods organise images according to visual similarity, while identification of motifs and historical interpretation remain dependent on source evidence and researcher validation.

Visual proximity in the resulting projection does not by itself demonstrate a historical relationship or direct influence.

---

## Repository contents

The repository preserves the principal data and computational outputs associated with the final corpus, including:

- master metadata;
- PixPlot metadata;
- processed motif crops;
- image-list data;
- fixed UMAP layout coordinates;
- PixPlot hotspot data;
- files used for the published data interfaces and visualisation.

The fixed UMAP coordinates preserve the arrangement analysed in the thesis. Re-running the computational workflow may generate a different two-dimensional projection.

---

## Software

The main visualisation was created with **PixPlot**, an open-source tool for exploring large image collections through image embeddings and dimensionality reduction.

PixPlot source code and documentation:  
[pleonard212/pix-plot on GitHub](https://github.com/pleonard212/pix-plot)

Additional Python scripts were used for motif cropping and for generating metadata-coloured point maps from the fixed UMAP coordinates.

---

## Access to the data

The published interface provides several ways of inspecting the corpus:

- [Interactive PixPlot visualisation](https://sabinna98.github.io/sabina98.github.io/index.html)
- [Browse Metadata](https://sabinna98.github.io/sabina98.github.io/metadata.html)
- [Data & Methods](https://sabinna98.github.io/sabina98.github.io/data.html)
- [Sources & Rights](https://sabinna98.github.io/sabina98.github.io/sources.html)

These interfaces provide access to and documentation for the research data preserved in this repository.

---

## Reuse

The workflow can be adapted to other image-based cultural heritage collections in which visual details need to be extracted, described through metadata, and compared computationally.

The dataset itself is specific to the reception history examined in the thesis. Its classifications and source relationships were created for this research context and should not be treated as a universal taxonomy of Minoan ornament.

---

## AI-assisted coding

ChatGPT by OpenAI was used as a supporting tool during selected technical stages of the project. It assisted with the development, debugging, and revision of Python code for the polygon-cropping interface and metadata-coloured point maps generated from the fixed UMAP coordinates, as well as with the HTML, CSS, and JavaScript used for the GitHub Pages interface.

The tool did not select the corpus, determine crop boundaries, classify motifs, establish historical source relationships, or interpret the computational results. All code was run, tested, and corrected on the project files by the author.

---

## Image rights

This repository was created for non-commercial academic research.

Copyright and reproduction rights for source images remain with the respective museums, archives, photographers, publishers, designers, or other rights holders.

Metadata, links, and research annotations included in the repository do not grant permission for further reproduction or reuse of source images. Users should consult the original institutional or bibliographic record and its rights statement before reusing an image.

---

## Author

**Sabina Rzaeva**  
Master’s Degree in Digital and Public Humanities  
Ca’ Foscari University of Venice  
2026

---

## Citation

Rzaeva, Sabina. *The Reception of Minoan Motifs in Modern and Contemporary Textiles and Fashion: Digital Analysis through Computational Image Clustering*. Master’s research project, Ca’ Foscari University of Venice, 2026.
