---
title: "Comparing different nonlinear dimensionality reduction techniques for data-driven unsteady fluid flow modeling"
date: 2022-11-01
publishDate: 2023-07-30T17:13:55.276529Z
authors: [admin, "Scott T. M. Dawson", "Amirhossein Arzani"]
publication_types: ["2"]
abstract: "Computational fluid dynamics (CFD) is known for producing high-dimensional spatiotemporal data. Recent advances in machine learning (ML) have introduced a myriad of techniques for extracting physical information from CFD. Identifying an optimal set of coordinates for representing the data in a low-dimensional embedding is a crucial first step toward data-driven reduced-order modeling and other ML tasks. This is usually done via principal component analysis (PCA), which gives an optimal linear approximation. However, fluid flows are often complex and have nonlinear structures, which cannot be discovered or efficiently represented by PCA. Several unsupervised ML algorithms have been developed in other branches of science for nonlinear dimensionality reduction (NDR), but have not been extensively used for fluid flows. Here, four manifold learning and two deep learning (autoencoder)-based NDR methods are investigated and compared to PCA. These are tested on two canonical fluid flow problems (laminar and turbulent) and two biomedical flows in brain aneurysms. The data reconstruction capabilities of these methods are compared, and the challenges are discussed. The temporal vs spatial arrangement of data and its influence on NDR mode extraction is investigated. Finally, the modes are qualitatively compared. The results suggest that using NDR methods would be beneficial for building more efficient reduced-order models of fluid flows. All NDR techniques resulted in smaller reconstruction errors for spatial reduction. Temporal reduction was a harder task; nevertheless, it resulted in physically interpretable modes. Our work is one of the first comprehensive comparisons of various NDR methods in unsteady flows."
featured: true
publication: "*Physics of Fluids*"
url_pdf: "http://www.sci.utah.edu/publications/Csa2022a/5.0127284.pdf"
url_code: "https://github.com/amir-cardiolab/Nonlinear-dimensionality-reduction"
url_video: "https://www.youtube.com/watch?v=gTVQt9QVG1o" 
doi: "10.1063/5.0127284"
---

