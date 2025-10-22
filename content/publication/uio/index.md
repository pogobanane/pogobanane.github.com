---
title: 'uIO: Lightweight and Extensible Unikernels'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Masanori Misono
  - admin
  - Charalampos Mainas
  - Pramod Bhatotia

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-10-21T00:00:00Z'
doi: '10.1145/3698038.3698518'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *SoCC'24, ACM Symposium on Cloud Computing*
publication_short: In *SoCC'24*

abstract: |
  Unikernels specialize operating systems by tailoring the kernel for a specific application at compile time.
  While the specialized library OS approach provides a smaller OS imagethus improving the bootup process, performance, migration costs, and reliable/trusted computing base—at the same time, unikernels lack run-time extensibility, which is imperative to support “on-demand” auxiliary tasks and tools, e.g., debugging, monitoring, re-configuration, and system management and deployment in a typical cloud environment.
  Consequently, unikernels present a fundamental trade-off between slimness of the OS image size at the compile time vs. flexibility of supported auxiliary functionality at the run-time.
  This work strives to balance this trade-off by keeping the unikernel system image as minimal as possible to solely support the application functionality in the “common case”, while providing “on-demand" extensibility for auxiliary tasks at run-time.
  The key challenge is to support run-time extensibility through a generic interface in a safe manner.
  To this end, the paper presents uIO—a “safe overlay” abstraction to provide runtime extensibility in unikernels, while maintaining the unikernel benefits.
  In particular, uIO leverages a generic VirtIO-based interface to provide an overlay for auxiliary programs, i.e., users can load external programs into the unikernels’ address space and run them, i.e., “on-demand” extensibility through a generic file system interface.
  To provide safe execution within an overlay, uIO provides isolation mechanisms leveraging hardware-assisted memory isolation (MPK) and language-runtime-based execution (eBPF).
  We implement a prototype of uIO based on Unikraft and demonstrate its applicability to support a range of auxiliary use cases.
  uIO incurs negligible performance overheads for application execution in the common case while providing run-time extensibility to support auxiliary use cases.

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

url_pdf: 'batching.pdf'
url_code: 'https://github.com/TUM-DSE/uio'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: 'slides.pdf'
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

