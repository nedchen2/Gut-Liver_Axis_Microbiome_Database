# Gut-Liver Axis Microbiome Database (GLiMD)
The Gut-Liver Axis Microbiome Database (GLiMD) is a comprehensive, curated resource of shotgun metagenomic sequencing data from gut microbiota, systematically aggregated from publicly available studies on liver disease. 

- By integrating this data, the resource aims to facilitate the discovery of microbial biomarkers, functional pathways, and host-microbe interactions critical to liver health and disease.



**Core Components & Features:**

- **Curated Data Collection:** We have systematically aggregated raw and processed sequencing data from public repositories (e.g., NCBI SRA, ENA) related to liver conditions such as MASLD/MASH, Alcoholic Liver Disease, Cirrhosis, and Hepatocellular Carcinoma.
- **Standardized Processing:** All data is uniformly processed using state-of-the-art bioinformatic pipelines (e.g.,  kraken2 + bracken/MetaPhlAn for taxonomy, HUMAnN for function) to ensure cross-study comparability and eliminate batch effects.
- **Rich Metadata:** Each sample is annotated with extensive and harmonized metadata, including disease etiology, severity stage, patient demographics, and clinical biomarkers, enabling powerful stratified analyses.
- **Interactive Interface:** GLiMD offers a user-friendly web interface that allows researchers to query, visualize, and download specific datasets without requiring advanced bioinformatic skills.
- **Integrated Analysis Tools:** The platform provides built-in tools for basic comparative analyses, such as differential abundance testing (taxa and genes), diversity calculations, and functional pathway enrichment.



**Primary Aims & Utility:**

- **Identify Diagnostic Biomarkers:** Discover microbial species or gene signatures that can distinguish between different liver disease states.
- **Understand Mechanism:** Elucidate the functional potential of the microbiome in liver disease pathogenesis through analysis of metabolic pathways.
- **Facilitate Meta-Analyses:** Empower robust, large-scale meta-analyses by providing a pre-processed, harmonized dataset from multiple independent studies.
- **Hypothesis Generation:** Serve as a foundational resource for generating new hypotheses about the role of microbes in liver health.



**Future Directions:** 

- The currently taxonomic profiling and functional profiling heavily depends on the database. The profile for each studies are expected to update annually.

- We plan to create a R package for quick microbiome analysis.

