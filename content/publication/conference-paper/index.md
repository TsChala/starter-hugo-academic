---
title: 'Comparing different nonlinear dimensionality reduction techniques for data-driven unsteady fluid flow modeling'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - tschala
  - Scott Dawson
  - Amirhossein Arzani

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2013-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Physics of Fluids*
publication_short: In *PoF*

abstract: Computational fluid dynamics (CFD) is known for producing high-dimensional spatiotemporal data. Recent advances in machine learning (ML) have introduced a myriad of techniques for extracting physical information from CFD. Identifying an optimal set of coordinates for representing the data in a low-dimensional embedding is a crucial first step toward data-driven reduced-order modeling and other ML tasks. This is usually done via principal component analysis (PCA), which gives an optimal linear approximation. However, fluid flows are often complex and have nonlinear structures, which cannot be discovered or efficiently represented by PCA. Several unsupervised ML algorithms have been developed in other branches of science for nonlinear dimensionality reduction (NDR), but have not been extensively used for fluid flows. Here, four manifold learning and two deep learning (autoencoder)-based NDR methods are investigated and compared to PCA. These are tested on two canonical fluid flow problems (laminar and turbulent) and two biomedical flows in brain aneurysms. The data reconstruction capabilities of these methods are compared, and the challenges are discussed. The temporal vs spatial arrangement of data and its influence on NDR mode extraction is investigated. Finally, the modes are qualitatively compared. The results suggest that using NDR methods would be beneficial for building more efficient reduced-order models of fluid flows. All NDR techniques resulted in smaller reconstruction errors for spatial reduction. Temporal reduction was a harder task; nevertheless, it resulted in physically interpretable modes. Our work is one of the first comprehensive comparisons of various NDR methods in unsteady flows.Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://doi.org/10.1063/5.0127284

url_pdf: ''
url_code: 'https://github.com/amir-cardiolab/Nonlinear-dimensionality-reduction'
url_dataset: 'https://github.com/amir-cardiolab/Nonlinear-dimensionality-reduction'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
