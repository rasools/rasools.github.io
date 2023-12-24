---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Machine learning-based investigation of the cancer protein secretory pathway"

authors:
- Rasool Saghaleyni
- Azam Sheikh Muhammad
- Pramod Bangalore
- Jens Nielsen
- Jonathan L. Robinson
date: "2023-12-14"
doi: "https://doi.org/10.1016/j.celrep.2022.110936"

# Schedule page publish date (NOT publication's date).
# publishDate: {{ .Date }}

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "PLOS Computational Biology"
publication_short: ""

abstract: "Deregulation of the protein secretory pathway (PSP) is linked to many hallmarks of cancer, such as promoting tissue invasion and modulating cell-cell signaling. The collection of secreted proteins processed by the PSP, known as the secretome, is often studied due to its potential as a reservoir of tumor biomarkers. However, there has been less focus on the protein components of the secretory machinery itself. We therefore investigated the expression changes in secretory pathway components across many different cancer types. Specifically, we implemented a dual approach involving differential expression analysis and machine learning to identify PSP genes whose expression was associated with key tumor characteristics: mutation of p53, cancer status, and tumor stage. Eight different machine learning algorithms were included in the analysis to enable comparison between methods and to focus on signals that were robust to algorithm type. The machine learning approach was validated by identifying PSP genes known to be regulated by p53, and even outperformed the differential expression analysis approach. Among the different analysis methods and cancer types, the kinesin family members KIF20A and KIF23 were consistently among the top genes associated with malignant transformation or tumor stage. However, unlike most cancer types which exhibited elevated KIF20A expression that remained relatively constant across tumor stages, renal carcinomas displayed a more gradual increase that continued with increasing disease severity. Collectively, our study demonstrates the complementary nature of a combined differential expression and machine learning approach for analyzing gene expression data, and highlights key PSP components relevant to features of tumor pathophysiology that may constitute potential therapeutic targets."

# Summary. An optional shortened abstract.
summary: "One of the most challenging features in diagnosing and treating cancer is its heterogeneity–the tissue of origin, gene mutation profile, patient, and local tumor environment are just a few of the many factors that can affect the pathophysiology and response to treatment of a particular cancer."

tags:
- Protein secretion
- Cancer
- Machine learning
- Secretory pathways
- Protein production

categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://pdf.sciencedirectassets.com/280959/1-s2.0-S2211124721X00253/1-s2.0-S2211124722007185/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjENL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCICusYdO133DtnO6UNtr7i2cUpgIAPzbAFva2eCle0qNbAiEAt1QMUpIw6rnaubvdI4bowA1bOxM72z3jm4KzP96aJ38qswUIWxAFGgwwNTkwMDM1NDY4NjUiDIUkTSXcmc7PQ%2FZuqSqQBdUclNWx0Y%2FU5PbfNu61mzrnaPyfZHxHz9nBYD5uCbrfZHMBFErKDd9ZhtTTgL0yYIoS%2BKpxk9XDO%2Bwv8xOxnyYBg33PW8eEuk1JClVAAZPoEv4RETGv9d5ZZeqlpEDy783rSDDka4eCgnGAp2IgLnLxmcqBV6cGQznwaFVW6cSCO5EcBc%2F4AAmwWKDaQ9E%2Ff5R7IYhvgRdHPZ3xN0ErQa39vcWqSexUDrMetfvyBVwKNjUDY5ux8tDUVDb5EMshKv%2FiGSWaaoB3WZYTijhas6CsBbQ3B515dM0ZI8fMsaMyNwGkIXiVuDaP8e4Yv1pBfZjFNAnDVYsJaUyXX4Rgugfir54EnbQB5PEvS9TP7aumiYyuP1yRuNhIvxr38QQQwZnxL8vShLbwj2len5LL%2BqiWSSnm5f3HkjHjZCFbZxaZIsdh1NH6igCz1TYdYNgUfw2q4%2FBk3gj1ZyrRlvxiknrTyoLXoOSxHJUJMhHbecWqdSv5q1Z8HFeGzY19dCqCpjwfehVwzg%2FiJZOmYiixYbdTsRASux81ZUJjYo6tDCwF0HDBJ%2BXhQrvD3pK5oj6KUyAFv%2B4tsuqI4funB3YIfbNziwRU0sqK5i4Nv005Cm4NXmtyUyIwhajf8ptNkmSzDaJtweOQBVXTvvvXT%2F%2BWH%2FxunwpJNmBPoeW6HD6jydHHfNHDTFD8MODLVhLNOHErSzu3%2Fv5obDcw24UneGGCWEeFmS%2Ba4MHK27gxh5SycqCFybNE57u%2BpNfZiJuLq3y4FEDHm3iQ1LTCozzTyMufthdazCwMgAZjXj5mUqHhMNbtQlV%2F5xIU0LhxcdRUuzIkuUhe%2F26d8xVSZF9KrWetJU2DzoHzzviUp96KrsFO9Yp1MKP%2Bn6wGOrEBQeXs1uXjmUj59HiQpavwDTTdWjCJ%2BHq2lICF0FhRlJmNHGTgv2ICSPJqHQbFltsYnslIdnnV5lZau%2BOHumpMYk8WpetVlXavi9pUQZNuh6M%2BbjElOxdJsY9l5CSGUCap%2FqmoGentnVKQG6yFmNf2Yj0nYmKAeBhHfjFGsgeB3ea0YnNThFtIPSjuBPI5KIrhUN9LfcN%2F6ZqiQD%2BJNOgp4jm%2FZ7hu5iyjfp3IBzohv8pW&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231224T105946Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYYIOYN2U7%2F20231224%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=fadcaaa044ff1a12f980ea3687e9cc47b1c62cddb48338cca4e38d8ad2049d89&hash=69875836d85ee65968f7c592575bd48be95ea9ccd14cec094ee12085de331201&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2211124722007185&tid=spdf-8058c31e-0381-4c37-83e8-98240a8e38bf&sid=ca152db81ec8b349615aa4a565d8223900ffgxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=11065d520759535850&rr=83a856327a2c7367&cc=se
url_code: https://github.com/SysBioChalmers/CancerProteinSecretionML
url_dataset: https://zenodo.org/records/4542854
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Source: https://zenodo.org/records/6519745#.YnN_TPNBwUE"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---