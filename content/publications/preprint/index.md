---
title: "FastAvatar: Towards Unified Fast High-Fidelity 3D Avatar Reconstruction with Large Gaussian Reconstruction Transformers"
authors:
- Yue Wu
- admin
- Wen Li
- Yuxi Lu
- Kairui Feng
- Xuanhong Chen

date: "2025-08-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "Submitted to ICLR 2025"
publication_short: "In Submission, Submitted to *ICLR 2025*"

abstract: "Despite significant progress in 3D avatar reconstruction, it still faces challenges such as high time complexity, sensitivity to data quality, and low data utilization. We propose FastAvatar, a feedforward 3D avatar framework capable of flexibly leveraging diverse daily recordings (e.g., a single image, multi-view observations, or monocular video) to reconstruct a high-quality 3D Gaussian Splatting (3DGS) model within seconds, using only a single unified model. FastAvatar's core is a Large Gaussian Reconstruction Transformer featuring three key designs: First, a variant VGGT-style transformer architecture aggregating multi-frame cues while injecting initial 3D prompt to predict an aggregatable canonical 3DGS representation; Second, multi-granular guidance encoding (camera pose, FLAME expression, head pose) mitigating animation-induced misalignment for variable-length inputs; Third, incremental Gaussian aggregation via landmark tracking and sliced fusion losses. Integrating these features, FastAvatar enables incremental reconstruction, i.e., improving quality with more observations, unlike prior work wasting input data. This yields a quality-speed-tunable paradigm for highly usable avatar modeling. Extensive experiments show that FastAvatar has higher quality and highly competitive speed compared to existing methods."

# Summary. An optional shortened abstract.
summary: "The paper proposes FastAvatar, a unified, feedforward framework that reconstructs high-quality 3D avatars in seconds from single images, videos, or multi-view inputs. With multi-granular guidance and incremental Gaussian aggregation, its VGGT-style architecture aggregates multi-frame cues, incorporates pose and expression guidance, and fuses Gaussians for real-time, high-fidelity avatars, outperforming existing methods in both speed and quality."

tags:
- 3D Vision

featured: true

#hugoblox:
#  ids:
#    arxiv: 2508.19754

links:
- type: preprint
  name: arxiv
  provider: arxiv
  id: 2508.19754
- type: code
  url: https://github.com/TyrionWuYue/FastAvatar?tab=readme-ov-file
#- type: slides
#  url: https://www.slideshare.net/
#- type: dataset
#  url: "#"
#- type: poster
#  url: "#"
#- type: source
#  url: "#"
#- type: video
#  url: https://youtube.com
#- type: custom
#  label: Custom Link
#  url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'More Info: [**Repo**](https://github.com/TyrionWuYue/FastAvatar?tab=readme-ov-file)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

###


> [!DETAIL]
> ### 🔥 Overview
> FastAvatar is a feedforward 3D avatar framework capable of flexibly leveraging diverse daily recordings (e.g., a single image, multi-view observations, or monocular video) to reconstruct a high-quality 3D Gaussian Splatting (3DGS) model within seconds, using only a single unified model.
> ### 📹 Demo
> **Self Reenacted**
> ![self_reenacted](self_001.gif)
> **Cross Reenacted**
> ![cross_reenacted](cross_001.gif)
> **Multi-view & Incremental Reconstruction**
> ![multiview](multiview_001.gif)


[//]: # (Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images]&#40;https://docs.hugoblox.com/content/writing-markdown-latex/&#41;.)

