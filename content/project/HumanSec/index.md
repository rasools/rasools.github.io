---
title: HumanSec
summary: The HumanSec toolbox advances the reference human genome-scale metabolic model by integrating protein-specific reactions from our proteomics dataset. It delves into the competition for resources between host cell proteins and recombinant protein production, aiming to create tailored protein secretion models for cell lines. By analyzing metabolomics data, it identifies crucial genes and pathways influencing protein production, offering potential for targeted cell factory design. However, this progress is acknowledged cautiously due to the inherent complexities of this research area. HumanSec also explores protein production pathways in diseases and aims to contribute to understanding protein folding mechanisms in pathological conditions, acknowledging the vast unknowns in this field.

tags:
  - protein secretion
  - cell-line development
  - protein production
  - genome-scale modeling
  - human cell line
  - GEM
  - HumanSec
date: '2022-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/addcellorg
#   - icon: linkedin
#     icon_pack: fab
#     name: Follow
#     url: https://www.linkedin.com/company/addcell/
url_code: 'https://github.com/rasools/HumanSec'
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

The demand for greater efficiency and quality of protein production in biotechnology is rapidly increasing due to substantial advances in drug discovery (Tambuyzer et al., 2020) and the need for highly effective pharmaceutical proteins for the treatment of severe diseases, such as cancer (Kintzing et al., 2016). Chinese hamster ovary (CHO) cells are the current standard host for the production of a wide range of recombinant proteins partly due to the ability to generate similar post-translational modifications (PTMs) to those in humans, which is often a requirement for complex therapeutic proteins (Orellana et al., 2015; Meleady 2017; Davy et al. 2017). However, the PTM pattern from CHO cells is not identical to human PTMs (Dumont et al., 2016) and the incompatibility with some types of proteins negatively affects drug efficacy, potency, or stability (Kuriakose et al. 2016; Goh and Ng 2017). Therefore, besides further development of the CHO cell line to meet the high-quality PTM requirements and increased yields (Datta et al. 2013; Koffas et al., 2018; Liang et al., 2020; Tejwani et al., 2018; Fouladiha et al., 2020; Wang et al., 2020), a lot of focus on improving hosts for biopharmaceutical production is on cell factories derived from human cells with the natural ability of generating human PTMs, such as the human embryonic kidney 293 (HEK293) cells (Almo and Love 2014; Malm et al., 2020; Tegel et al., 2020).

Although human-derived cell lines benefit from the ability to generate human PTMs, challenges still remain, such as increasing the protein production titer (Chin et al., 2019; Dietmair et al., 2012; Mori et al., 2020) and creating a genetic engineering toolbox with specialized tools for human cells (Xu and Qi 2019). Recent publications have pursued some of these challenges, including the aim to increase the protein production and secretion power either by cell-line development approaches (Chin et al., 2019; Rahimpour et al., 2013) or cell culture process optimization (Schwarz et al., 2019), as well as to increase the quality of the secreted proteins by engineering folding and PTM pathways (Meuris et al., 2014; Del Val et al., 2016; Liang et al., 2020; Behrouz et al., 2020). However, despite the current knowledge of protein production and secretion in eukaryotic cells, there is still notable ambiguity in understanding and predicting the production and secretion rates as well as product quality under different conditions (Kafri et al., 2016; Liu et al. 2016). This is due to the complexity and presence of many specific biochemical steps across multiple cell organelles that orchestrate, as well as define, the rates of production and secretion of each protein (Kaufman and Popolo 2018; Kafri et al., 2016). Accordingly, the limited understanding of the biology behind the protein production process, combined with the continuously increasing demands on production quantity from industry and product quality from regulatory bodies, result in a high risk of production failure for many therapeutic proteins.