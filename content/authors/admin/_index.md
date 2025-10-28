---
# Display name
title: Peter Okelmann

# Name pronunciation (optional)
# name_pronunciation: Chien Shiung Wu

# Full name (for SEO)
first_name: Peter
last_name: Okelmann

# Status emoji
status:
  icon: 🐧

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: PhD Student

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Systems Research Group at TU Munich
    url: https://dos.cit.tum.de

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:okelmann@cit.tum.de'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/pogobanane
  - icon: brands/x
    url: https://twitter.com/peterokelmann
  # - icon: brands/instagram
  #   url: https://www.instagram.com/
  # - icon: brands/linkedin
  #   url: https://www.linkedin.com/
  - icon: academicons/google-scholar
    url: https://scholar.google.de/citations?user=LAeelzkAAAAJ&hl=de&oi=ao
  - icon: academicons/orcid
    url: https://orcid.org/0000-0001-6728-1335
  - icon: academicons/dblp
    url: https://dblp.org/pid/298/4088.html

interests:
  - (Confidential) Virtual Machines
  - Networking
  - IO device virtualization
  - Functional system definitions
  # - 'NixOS <img src="media/icons/NixOS_logo.svg" style="height: 1.2em; display: inline"/>'

education:
  - area: "Ongoing: Dr. rer. nat. Informatics (PhD)"
    institution: Technical University Munich
    date_start: 2020-12-01
    date_end: ''
    # summary: |
    #   Thesis: Building lightweight VMs for Function as a Service
  - area: MSc Informatics
    institution: Technical University Munich
    date_start: 2020-03-15
    date_end: 2022-03-15
    summary: |
      Thesis: Building lightweight VMs for Function as a Service

      Artifact: Container-like debuggability for minimal lambda-function VMs: <a href="https://github.com/pogobanane/lambda-pirate">λ🏴‍☠️ lambda-pirate</a> (see also <a href="/#papers">Vmsh [EuroSys'22]</a>)
    #   GPA: 3.8/4.0

    #   Courses included:
    #   - lorem ipsum dolor sit amet, consectetur adipiscing elit
    #   - lorem ipsum dolor sit amet, consectetur adipiscing elit
    #   - lorem ipsum dolor sit amet, consectetur adipiscing elit
  - area: BSc Informatics
    institution: Technical University Munich
    date_start: 2015-10-15
    date_end: 2020-03-15
    summary: |
      Thesis: Performance analysis of the VPP software router

      Artifact: <a href="/#papers">Adaptive batching [NetSoft'21]</a>
    #   GPA: 3.4/4.0
    #
    #   Courses included:
    #   - lorem ipsum dolor sit amet, consectetur adipiscing elit
    #   - lorem ipsum dolor sit amet, consectetur adipiscing elit
    #   - lorem ipsum dolor sit amet, consectetur adipiscing elit
work:
  - position: Research Staff
    company_name: Technical University Munich
    company_url: ''
    company_logo: ''
    date_start: 2022-03-01
    date_end: ''
    # summary: |
    #   - Contributing to [Vmsh [EuroSys'22]](/#papers)
    #   - Virtual device development for KVM
  - position: Research Internship
    company_name: Nokia Bell Labs
    company_url: https://www.nokia.com/bell-labs/
    company_logo: ''
    date_start: 2025-06-15
    date_end: 2025-10-15
    summary: |
      - Software and Data Systems Research Lab
      - Advised by <a href="https://iakkus.github.io/">Istemi Ekin Akkus</a>, <a href="https://www.ruichuan.org/">Riuchuan Chen</a>, and <a href="https://www.nokia.com/people/ivica-rimac/">Ivica Rimac</a>
      - Topic: Closing the performance gap of Confidential Virtual Machines for Virtual Network Functions
  - position: Student Assistant (HiWi)
    company_name: Technical University Munich
    company_url: ''
    company_logo: ''
    date_start: 2021-09-01
    date_end: 2021-10-31
    summary: |
      - Contributing to <a href="/#papers">Vmsh [EuroSys'22]</a>
      - Virtual device development for KVM
  - position: Full stack developer and consultant
    company_name: Moonlight GmbH & Co. KG
    company_url: ''
    company_logo: ''
    date_start: 2020-11-01
    date_end: 2021-01-15
    summary: |
      - Developing web-based digital signage
      - IT consulting
  - position: Embedded Software Developer
    company_name: iKudrus GmbH
    company_url: ''
    company_logo: ''
    date_start: 2020-10-01
    date_end: 2020-11-30
    summary: |
      - Arduino development
      - Measuring drift and jitter of mechanical clocks with microsecond-accuracy

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: C/Cpp, Rust, Java, ...
        description: ''
        percent: 99
        icon: code-bracket
      - name: Networking
        description: ''
        percent: 99
        icon: code-bracket
      - name: NixOS (DevOps)
        description: ''
        percent: 99
        icon: code-bracket
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Climbing
        description: ''
        percent: 60
        icon: person-simple-walk
      - name: Hiking
        description: ''
        percent: 60
        icon: person-simple-walk
      - name: Self-hosting
        description: ''
        percent: 80
        icon: code-bracket

languages:
  - name: German
    percent: 100
  - name: English
    percent: 100
  - name: Italian
    percent: 25

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Best Artifact Award (Honorable mention)
    url: https://2022.eurosys.org/index.html@p=652.html
    date: '2022-04-05'
    awarder: EuroSys'22
    summary: |
      For the paper "VMSH: hypervisor-agnostic guest overlays for VMs"
    # icon: hero/academic-cap
    #    summary: |
    #      I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.
#   - title: Blockchain Fundamentals
#     url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#     date: '2023-07-01'
#     awarder: edX
#     icon: edx
#     summary: |
#       Learned:
#       - Synthesize your own blockchain solutions
#       - Gain an in-depth understanding of the specific mechanics of Bitcoin
#       - Understand Bitcoin’s real-life applications and learn how to attack and destroy Bitcoin, Ethereum, smart contracts and Dapps, and alternatives to Bitcoin’s Proof-of-Work consensus algorithm
#   - title: 'Object-Oriented Programming in R'
#     url: https://www.datacamp.com/courses/object-oriented-programming-with-s3-and-r6-in-r
#     certificate_url: https://www.datacamp.com
#     date: '2023-01-21'
#     awarder: datacamp
#     icon: datacamp
#     summary: |
#       Object-oriented programming (OOP) lets you specify relationships between functions and the objects that they can act on, helping you manage complexity in your code. This is an intermediate level course, providing an introduction to OOP, using the S3 and R6 systems. S3 is a great day-to-day R programming tool that simplifies some of the functions that you write. R6 is especially useful for industry-specific analyses, working with web APIs, and building GUIs.
---

## About Me

Peter Okelmann is a PhD candidate with the [Systems Research Group](https://dos.cit.tum.de) at Technical University Munich.
His research interests include virtualization with containers or virtual machines, often at their intersection with networking.
Aside from his research, he sometimes contributes to [NixOS](https://nixos.org) as a maintainer.

In the past, he interned at [Nokia Bell Labs](https://www.nokia.com/bell-labs/), advised by [Istemi Ekin Akkus](https://iakkus.github.io/) and [Riuchuan Chen](https://www.ruichuan.org/), where he addressed the I/O performance gap imposed by hardware confidentiality onto virtual machines.

