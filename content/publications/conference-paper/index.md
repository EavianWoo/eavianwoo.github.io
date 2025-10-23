---
title: 'SinGS: Animatable Single-Image Human Gaussian Splats with Kinematic Priors'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
#  - name: Xuanhong Chen
#    url: https://scholar.google.com/citations?user=UuCqlfEAAAAJ
#  - name: Wen Li
#    url: https://github.com/lililuya
  - Xuanhong Chen
  - Wen Li
  - Shunran Jia
  - Hualiang Wei
  - Kairui Feng
  - Jialiang Chen
  - Yuhan Li
  - Ang He
  - Weimin Zhang
  - Bingbing Ni
  - Wenjun Zhang
#  - name: Bingbing Ni
#    url: https://scholar.google.com/citations?hl=en&user=eUbmKwYAAAAJ
#  - name: Wenjun Zhang
#    url: https://ee.sjtu.edu.cn/en/FacultyDetail.aspx?id=14&infoid=153&flag=153

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2025-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: CVPR 2025
publication_short: In *CVPR 2025*

abstract: "Despite significant advances in accurately estimating geometry in contemporary single-image 3D human reconstruction, creating a high-quality, efficient, and animatable 3D avatar remains an open challenge. Two key obstacles persist: incomplete observation and inconsistent 3D priors. To address these challenges, we propose SinGS, aiming to achieve high-quality and efficient animatable 3D avatar reconstruction. At the heart of SinGS are two key components: Kinematic Human Diffusion and Geometry-Preserving 3D Gaussain Splatting. The former is a foundational human model that samples within pose space to generate a highly 3D-consistent and high-quality sequence of human images, inferring unseen viewpoints and providing kinematic priors. The latter is a system that reconstructs a compact, high-quality 3D avatar even under imperfect priors, achieved through a novel semantic Laplacian regularization and a geometry-preserving density control strategy that enable precise and compact assembly of 3D primitives. Extensive experiments demonstrate that SinGS enables lifelike, animatable human reconstructions, maintaining both high quality and inference efficiency (up to 70FPS)."

# Summary. An optional shortened abstract.
summary: The Paper presents SinGS, a framework for efficient and high-quality animatable 3D human reconstruction from a single image. It integrates Kinematic Human Diffusion to infer unseen poses and Geometry-Preserving Gaussian Splatting to build compact, realistic avatars, achieving lifelike performance at real-time speeds.

tags:
  - 3D Vision

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/CVPR52734.2025.00523

# Custom links
links:
  - type: paper
    url: https://openaccess.thecvf.com/content/CVPR2025/html/Wu_SinGS_Animatable_Single-Image_Human_Gaussian_Splats_with_Kinematic_Priors_CVPR_2025_paper.html
  - type: code
    url: https://github.com/EavianWoo/SinGS
#  - type: dataset
#    url: https://github.com/HugoBlox/hugo-blox-builder
#  - type: slides
#    url: https://www.slideshare.net/
#  - type: source
#    url: https://github.com/HugoBlox/hugo-blox-builder
  - type: poster
    url: 
  - url: https://eavianwoo.github.io/singsPage/
    name: "page"
    type: slides
  - type: video
    url: https://youtu.be/2NVqoVNVmjY

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'More Info: [**Page**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: ""
---
###

> [!DETAIL]
> ### ⛏ Reconstruction
> ![rec](RecBrief.mp4)
> ### ⛹ Animation
> ![Ani](AniBrief.mp4)