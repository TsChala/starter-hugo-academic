---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Enhancing corrupt cardiovascular flow data with machine learning
event: SB3C 2023
event_url: https://sb3c.org
location: Vail, CO, US
address:
  street:
  city:
  region:
  postcode:
  country:
summary: Summer Biomechanics, Bioengineering, and Biotransport Conference 2023 
abstract:

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2023-06-05T11:52:32-06:00
#date_end: 2023-07-30T11:52:32-06:00
all_day: true

# Schedule page publish date (NOT event date).
publishDate: 2023-06-05T11:52:32-06:00

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
url_pdf: 'uploads/Csala_SB3C23.pdf'
url_video: "https://youtu.be/26jsUECMLNU"

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
projects: []
---
I presented my work in the Machine Learning in Biofluids section.

**Summary:**

Obtaining clean, high resolution velocity measurements of blood flow inside small arteries such as cerebral vasculature is challenging, as the existing experimental techniques have several limitations. Time-resolved three-dimensional phase contrast magnetic resonance imaging (4D flow MRI) is a popular approach in research settings, however it is constrained by low spatio-temporal resolution, noise, and other artifacts. Particle image velocimetry (PIV) often considered the gold-standard in experimental fluid dynamics also suffers from some limitations. Therefore, handling corrupt blood flow data is key challenge towards developing more accurate and robust cardiovascular flow models. There are well developed algorithms in the machine learning community that can tackle similar issues, such as data imputation, denoising or outlier detection. Existing methods have been less frequently used and leveraged for complex real-world fluid flow problems, such as cardiovascular flows. Specifically, we do not understand which one of these approaches commonly used in the machine learning community perform better for hemodynamics data. This study investigates and compares several techniques for filling in missing
values and denoising unsteady blood flow data in an image-based 3D intracranial aneurysm model
