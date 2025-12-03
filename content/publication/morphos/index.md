---
title: 'MorphOS: An Extensible Networked Operating System'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Ilya Meignan--Masson
  - Masanori Misono
  - Pramod Bhatotia

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-10-01T00:00:00Z'
doi: '10.1145/3768977'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *CoNEXT'25, Proc. ACM Netw.*
publication_short: In *CoNEXT'25*

abstract: |
  This paper introduces MorphOS, an extensible networked operating system that addresses the runtime inflexibility of unikernels for dynamic, stateful network-intensive applications like Virtual Network Functions (VNFs).
  While unikernels offer superior performance and minimal resource overheads, their traditional update mechanisms require costly rebuilds and restarts, leading to service disruption and state loss.
  MorphOS addresses this by integrating eBPF to enable dynamic, verified code execution for seamless updates to packet processing logic.
  It employs an out-of-band verification service to offload computationally intensive verification tasks and utilizes hardware-assisted memory isolation (Memory Protection Keys) for enhanced execution hardening.
  Our evaluation of MorphOS with four VNF implementations demonstrates significant benefits:
  MorphOS drastically reduces reconfiguration time, effectively amortizes verification costs, and achieves up to 3× better performance compared to Linux-based VNF deployments, all while preserving the inherent lightweightness of unikernels.
  MorphOS thus paves the way for adaptable, efficient, and state-preserving networked applications in cloud environments.


# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
#   - Large Language Models

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'morphos.pdf'
url_code: 'https://github.com/TUM-DSE/morphos'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
url_slides: 'slides.pdf'
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
slides: ""

---

