---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Comparing different nonlinear dimensionality reduction tehcniques for data-driven unsteady fluid flow modeling
event: USNC/TAM 2022
event_url: https://www.usnctam2022.org
location: Austin, TX, US
address:
  street:
  city:
  region:
  postcode:
  country:
summary: US National Congress on Theoretical and Applied Mechanics 2022
abstract: 

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-06-22T11:52:22-06:00
#date_end: 2023-07-30T11:52:22-06:00
all_day: true

# Schedule page publish date (NOT event date).
publishDate: 2022-06-22T11:52:22-06:00

authors: []
tags: []

# Is this a featured event? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your event's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video: "https://www.youtube.com/watch?v=gTVQt9QVG1o" 
url_poster: '/uploads/SISSA_poster.pdf'

# Markdown Slides (optional).
#   Associate this event with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["NDR"]
---
I presented my work in the Methods for Data-Driven Modeling of Unsteady Fluid Flows Minisymposium.

**Summary:**

Computational fluid dynamics (CFD) data are usually high dimensional, with millions of degrees of freedom in space
and thousands of timesteps. The first step of reduced order modeling is to identify a new set of coordinates, a low
dimensional embedding, that describe the underlying dominant structures in the data. This is usually done via
Proper Orthogonal Decomposition (POD), which gives the best linear approximation. Several nonlinear
dimensionality reduction (NDR) techniques, so-called manifold learning methods, have been developed in other
branches of science, which have not yet been extensively used for fluid flow data. These methods can discover the
nonlinear manifolds underlying the data, which can give a better representation than the linear hyper-plane obtained
by POD.

Herein, manifold learning techniques, e.g., Locally Linear Embedding (LLE), Kernel Principal Component Analysis
(KPCA), and Laplacian Eigenmaps (LEM) are investigated for generating low dimensional embeddings for CFD
data. Autoencoders are also implemented using deep neural networks. Simple unsteady flows (e.g., 2D flow around
a cylinder) and more challenging biomedical flows (e.g., pulsatile blood flow in diseased arteries) were analyzed.
Unlike POD, these methods need hyper-parameter tuning, but under the right circumstances, they can outperform
POD.

We compare data reconstruction between the methods and discuss the effect of hyperparameters. Data
reconstruction is not straightforward with certain NDR techniques, which will be discussed. Another challenge is
obtaining spatial and interpretable modes. We discuss the temporal vs. spatial arrangement of input data and its
influence on NDR mode extraction. Finally, the modes are qualitatively compared between the methods. The results
suggest that using these NDR methods instead of POD would be beneficial for building better reduced order
models.