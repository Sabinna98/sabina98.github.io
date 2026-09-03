# Minoan Motif Reception

## The Reception of Minoan Motifs in Modern and Contemporary Textiles and Fashion: Digital Analysis through Computational Image Clustering

A non-commercial research dataset developed as part of a Master’s thesis in Digital and Public Humanities at Ca’ Foscari University of Venice.

**Interactive PixPlot visualisation:**  
[Open the Minoan Motif Reception visualisation](https://sabinna98.github.io/sabina98.github.io/index.html)

**Project documentation and data interface:**  
[Open the project website](https://sabinna98.github.io/sabina98.github.io/about.html)

---

## Dataset overview

This repository contains the image corpus, metadata, and derived computational data used to investigate the reception of Minoan and Aegean Bronze Age motifs in modern textiles, stage costume, and fashion.

The dataset connects material from three historical layers:

- **Archaeological** — Minoan and Aegean Bronze Age objects and frescoes;
- **Publication** — images reproduced in archaeological books, plates, and early publications;
- **Reception** — modern and contemporary textiles, costume, and fashion.

The final computational corpus contains **180 motif crops**. Each crop isolates a motif from a larger parent image while preserving its connection to the original object or source.

The corpus currently includes:

- **180** motif crops;
- **3** corpus layers;
- **5** broad motif groups;
- **23** specific motif terms;
- **10** stored PixPlot hotspots.

The dataset was constructed for the comparative study of visual transmission across archaeological material, printed reproductions, and later design.

---

## Data structure

The repository preserves both descriptive metadata and files generated during the computational workflow.

Each motif crop is associated with information such as:

- filename;
- parent image;
- corpus layer;
- source type;
- source reference;
- object type;
- date or period;
- place of origin;
- current location;
- author or designer, where applicable;
- broad motif group;
- specific motif classification;
- bibliographic or institutional source;
- links to external records, where available.

The connection between a crop and its parent image is retained so that the computationally analysed fragment can be traced back to its original visual and historical context.

---

## Repository contents

The repository includes the main files required to inspect the corpus and reconstruct the published visualisation.

These include:

- **master metadata** — the fuller descriptive dataset used during corpus construction;
- **PixPlot metadata** — the metadata supplied to the visualisation environment;
- **processed motif crops** — the 180 images used in the final computational corpus;
- **UMAP coordinates** — the fixed two-dimensional coordinates of the published arrangement;
- **image list** — the correspondence between images and the generated PixPlot data;
- **hotspot data** — stored membership information for the ten PixPlot hotspots;
- **HTML, CSS, and JavaScript files** — the interface used to provide access to the data and visualisation.

The fixed UMAP coordinates are preserved because a new computational run can produce a different two-dimensional arrangement even when the underlying corpus remains unchanged.

---

## Computational visualisation

The corpus was visualised with **PixPlot**, using image embeddings and UMAP dimensionality reduction to arrange the motif crops according to computed visual similarity.

[**Open the interactive PixPlot visualisation →**](https://sabinna98.github.io/sabina98.github.io/index.html)

The visualisation can be used to:

- inspect the overall distribution of the 180 motif crops;
- move between visually proximate images;
- examine PixPlot hotspots;
- filter and compare images using metadata;
- trace relationships across archaeological, publication, and reception material.

Spatial proximity in the projection should not be interpreted as evidence of historical influence on its own. The computational arrangement functions as a discovery and comparison environment; possible relationships must be checked against metadata, provenance, publications, and close visual analysis.

---

## Corpus construction

The computational unit of the dataset is the **motif crop**, rather than the complete object or source image.

Motifs were extracted from parent images in order to reduce the influence of unrelated visual information and make recurrent ornamental and figurative forms more directly comparable.

The workflow consisted of:

1. identifying relevant archaeological, publication, and reception material;
2. recording source and object metadata;
3. extracting individual motif crops from parent images;
4. assigning descriptive motif categories;
5. preparing image and metadata files for PixPlot;
6. generating the computational visualisation;
7. comparing computed proximity with metadata and art-historical evidence.

The dataset therefore combines manually constructed art-historical metadata with computational visual organisation.

---

## Motif classification

Two levels of motif description are retained in the metadata.

**Broad motif groups** provide a higher-level classification for comparison across the corpus, while **specific motif terms** preserve more detailed distinctions between individual forms.

The classifications were assigned manually on the basis of visual analysis and source research. They are independent of the groups produced by the computational projection and can therefore be used to compare human classification with computed visual proximity.

---

## Reuse and reproducibility

The repository is intended to preserve the data structure and computational outputs associated with the thesis and to make the workflow inspectable and reusable.

The general workflow — construction of an image corpus, extraction of visual details, metadata modelling, computational image arrangement, and comparison between visual proximity and descriptive categories — can be adapted to other image-based cultural heritage collections.

The stored coordinates reproduce the arrangement used in the final research project. Re-running PixPlot or UMAP may result in a different projection and should therefore be treated as a new computational run rather than an exact reproduction of the published map.

---

## Web interfaces

The GitHub Pages environment provides several interfaces for inspecting the dataset:

- [**Interactive PixPlot visualisation**](https://sabinna98.github.io/sabina98.github.io/index.html)
- [**About the project**](https://sabinna98.github.io/sabina98.github.io/about.html)
- [**Explore the archive**](https://sabinna98.github.io/sabina98.github.io/explore.html)
- [**Data & Methods**](https://sabinna98.github.io/sabina98.github.io/data.html)
- [**Browse Metadata**](https://sabinna98.github.io/sabina98.github.io/metadata.html)
- [**Sources & Rights**](https://sabinna98.github.io/sabina98.github.io/sources.html)

These pages provide access to the repository data and documentation; they are not the primary research dataset themselves.

---

## AI-assisted coding

ChatGPT by OpenAI was used as a supporting tool during selected technical stages of the project. It assisted with the development, debugging, and revision of Python code for the polygon-cropping interface and metadata-coloured point maps generated from the fixed UMAP coordinates, as well as with the HTML, CSS, and JavaScript used for the GitHub Pages interface.

The tool did not select the corpus, determine crop boundaries, classify motifs, establish historical source relationships, or interpret the computational results. All code was run, tested, and corrected on the project files by the author.

---

## Image rights

This repository was created for non-commercial academic research.

Copyright and reproduction rights for source images remain with the respective museums, archives, photographers, publishers, designers, or other rights holders.

Metadata, links, and research annotations provided in this repository do not grant permission to reproduce source images. Users wishing to reuse an image should consult its original institutional or bibliographic source and the corresponding rights statement.

---

## Author

**Sabina Rzaeva**  
Master’s Degree in Digital and Public Humanities  
Ca’ Foscari University of Venice  
2026

---

## Citation

Rzaeva, Sabina. *The Reception of Minoan Motifs in Modern and Contemporary Textiles and Fashion: Digital Analysis through Computational Image Clustering*. Master’s research project, Ca’ Foscari University of Venice, 2026.
