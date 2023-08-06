---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Nonlinear Dimensionality Reduction of Fluid Flows"
summary: ""
authors: [admin]
tags:
  - Deep Learning
  - CFD
categories: []
date: 2023-07-30T20:09:57-06:00
math: true

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image: 
  caption: "Autoencoders architectures for spatial and temporal dimensionality reduction"
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/amir-cardiolab/Nonlinear-dimensionality-reduction"
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=gTVQt9QVG1o" 

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
<div style="text-align: justify"> 
Usually CFD data is very high dimensional, it is a necessity for the numerical schemes to converge. However, natural systems tend to live on low dimensional manifolds. The goal of dimensionality reduction is find a low dimensional embedding that preserves the important aspects of our data but representes it using much less information.

The most well known dimensionality reduction algorithm is Principal Component Analysis (PCA). In the fluid dynamics community it's usually referred to as Proper Orthogonal Decomposition (POD). It can be simply calculated using the Singular Value Decomposition (SVD): 

$\mathbf{X} = \mathbf{U} \mathbf{\Sigma} \mathbf{V}^{T}$

where $\mathbf{\Sigma}$ contains the singular values along the diagonal, $\mathbf{U}$ and $\mathbf{V}$ are the left and right singular vectors. Then we can keep only the $r$-largest singular values and corresponding singular values, leading to the best possible rank-$r$ linear reconstruction.

However, many real life phenomena, including most fluid flows, is highly nonlinear. Therefore, PCA might not lead to the best embedding. In this project we explored how certain manifold learning and deep learning algorithms compare to PCA, applied to unsteady fluid flows.

</div>

|![Cylinder modes](cylinder_modes.png)|
|:--:| 
| *First few spatial modes for flow over a cylinder with different methods* |

<div style="text-align: justify">
We investigated both reducing the temporal and spatial size of our data. Temporal reduction can be used to obtain interpretable modes that can help understand the underlying coherent structured in the flow. Spatial dimensionality reduction is used for creating reduced order models.

Four test cases were investigated: vortex shedding behind a cylinder, a 2D slice of a turbulent channel flow, flow inside an ICA and an MCA aneurysm. We were able to show that under the right circumstances all nonlinear methods can outperform PCA in terms of reconstruction error for all cases. However, many of the desirable properties of PCA (orthogonal and ranked modes, both temporal and spatial reconstruction, computationally cheap) are not inherited by these methods.

</div>


<!-- <img src="cylinder_modes.png"
     alt="Markdown Monster icon"
     style="float: left; margin-right: 10px;" /> -->