# Minoan Motif Reception

## The Reception of Minoan Motifs in Modern and Contemporary Textiles and Fashion: Digital Analysis through Computational Image Clustering

A non-commercial academic research project developed as part of a Master’s thesis in Digital and Public Humanities at Ca’ Foscari University of Venice.

### About the project

This project examines the reception of Minoan and Aegean Bronze Age motifs in modern textiles, stage costume, and fashion. It brings archaeological objects, early archaeological publications, and later reception material into a connected digital environment where images can be explored through visual similarity and checked against structured metadata and source documentation.

The final computational corpus contains 180 motif crops organised through three historical layers:

- archaeological material;
- publication sources;
- modern reception material.

The visualisation was produced with PixPlot and uses a UMAP projection to arrange the prepared images according to computed visual similarity. Visual proximity is treated as a starting point for comparison and does not by itself establish a historical relationship between objects.

### Project structure

The GitHub Pages environment contains several connected views:

- **About** — introduction to the project and corpus;
- **Explore** — explanation of the archive structure and navigation;
- **Data & Methods** — methodological summary and access to project data;
- **Browse Metadata** — searchable and filterable metadata catalogue;
- **Visualization** — the interactive PixPlot environment;
- **Sources & Rights** — source institutions and image-rights information.

### Corpus

The final corpus contains:

- **180** motif crops
- **3** corpus layers
- **5** broad motif groups
- **23** specific motif terms
- **10** stored PixPlot hotspots

Each motif crop remains connected to its parent image and to descriptive information about its motif, object, corpus layer, chronology, author or designer, and source.

### Data

The repository includes the metadata and generated files used by the published visualisation, including:

- master metadata;
- PixPlot metadata;
- fixed UMAP layout coordinates;
- image list;
- hotspot membership data;
- processed motif crops.

The preserved coordinates correspond to the final published arrangement. A new computational run may generate a different two-dimensional layout.

### Method

The workflow combines:

1. corpus construction;
2. motif extraction from parent images;
3. metadata modelling;
4. computational visualisation with PixPlot;
5. comparison of computational proximity with metadata, provenance, publications, and close visual analysis.

The project follows a human-in-the-loop approach: computational methods organise visual similarities, while historical interpretation remains dependent on source evidence and researcher validation.

### AI-assisted coding

ChatGPT by OpenAI was used as a supporting tool during selected technical stages of the project. It assisted with the development, debugging, and revision of Python code for the polygon-cropping interface and point maps generated from the fixed UMAP coordinates, as well as with the HTML, CSS, and JavaScript of the GitHub Pages prototype.

The tool did not select the corpus, define crop boundaries, classify motifs, establish source relations, or interpret the visual results. All code was run, tested, and corrected on the project files by the author.

### Image rights

The project is non-commercial and was created for academic research.

Copyright and reproduction rights for source images remain with the respective museums, archives, photographers, publishers, or other rights holders. Inclusion of metadata or a source link does not grant permission for further reproduction or reuse.

Users should consult the original institutional record and its rights statement before reusing any image.

### Author

**Sabina Rzaeva**  
Master’s Degree in Digital and Public Humanities  
Ca’ Foscari University of Venice  
2026

### Citation

Rzaeva, Sabina. *The Reception of Minoan Motifs in Modern and Contemporary Textiles and Fashion: Digital Analysis through Computational Image Clustering*. Master’s research project, Ca’ Foscari University of Venice, 2026.
