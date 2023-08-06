---
title: Manifold learning and deep autoencoders for nonlinear embedding of unsteady fluid flows

event: APS DFD 2022
event_url: https://www.apsdfd2022.org

location: Indianapolis, IN, US
#address:
#  street: Convention Center
#  city: Indianapolis
#  region: IN
#  country: United States

summary: APS Division of Fluid Dynamics 2022
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-11-22T13:00:00Z'
#date_end: '2030-06-01T15:00:00Z'
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  caption: ''
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/csalahunor
url_code: ''
url_pdf: ''
url_slides: ''
url_video: "https://www.youtube.com/watch?v=gTVQt9QVG1o" 
url_poster: '/uploads/SISSA_poster.pdf'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - NDR
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->

I presented my work in the [Nonlinear Dynamics: Machine Learning](https://meetings.aps.org/Meeting/DFD22/Session/U21.4) session.

**Abstract:** 

Computational fluid dynamics (CFD) is known for producing high-dimensional data in space and time. Modern data-driven modeling approaches present a myriad of techniques to extract physical information from these datasets and identify an optimal set of coordinates for representing them in a low-dimensional embedding. This is a crucial first step toward reduced order modeling, usually done via proper orthogonal decomposition (POD), which gives the best linear approximation. However, fluid flows are often highly complex with nonlinear structures. Several unsupervised machine learning algorithms have been developed in other branches of science for nonlinear dimensionality reduction (NDR), but have not yet been extensively used for fluid flow data. We investigate four manifold learning and two deep learning based NDR methods and compare them to POD. These are tested on two canonical fluid flow problems and biomedical flows in diseased arteries. We compare the performance of these methods and discuss the associated challenges. The temporal vs. spatial arrangement of input data and its influence on NDR mode extraction is investigated, and the obtained spatial modes are compared. Finite time Lyapunov exponents (FTLE) are calculated to facilitate flow physics interpretation.