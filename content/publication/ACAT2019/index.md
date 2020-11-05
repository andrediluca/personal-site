---
title: "Real-time reconstruction of long-lived particles at LHCb using FPGAs"
authors:
- Riccardo Cenci
- admin
- Federico Lazzari
- Michael J. Morello
- Giovanni Punzi

date: "2020-07-08T00:00:00Z"
doi: "http://dx.doi.org/10.1088/1742-6596/1525/1/012101"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Journal of Physics Conference Series

publication_short: In *J.Phys.Conf.Ser.*

abstract: Finding tracks downstream of the magnet at the earliest LHCb trigger level is not part of the baseline plan of the upgrade trigger, on account of the significant CPU time required to execute the search. Many long-lived particles, such as $K^S_0$ and strange baryons, decay after the vertex track detector, so that their reconstruction efficiency is limited. We present a study of the performance of a future innovative real-time tracking system based on FPGAs, developed within a R&D effort in the context of the LHCb Upgrade Ib (LHC Run 4), dedicated to the reconstruction of the particles downstream of the magnet in the forward tracking detector (Scintillating Fibre Tracker), that is capable of processing events at the full LHC collision rate of 30 MHz.

# Summary. An optional shortened abstract.
summary: Study  of  the  performance  of  a  future  innovative  real-time  tracking  system  based  on  FPGAs,developed within a R&D effort in the context of the LHCb Upgrade Ib (LHC Run 4), dedicatedto the reconstruction of the particles downstream of the magnet in the forward tracking detector(Scintillating Fibre Tracker), that is capable of processing events at the full LHC collision rateof 30 MHz.

# tags:
# - Source Themes
featured: true

links:
- icon: file-pdf
  icon_pack: fa
  name: PDF
  url: 2006.11067.pdf
- icon: arxiv
  icon_pack: ai
  name: arXiv
  url: https://arxiv.org/abs/2006.11067
- icon: inspire
  icon_pack: ai
  name: inspire
  url: https://inspirehep.net/literature/1802099
  

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project
---


{{< figure src="retina.png" title="Excitation level of the axial retina filled with SciFi subdetector hits from a single fully simulated event (left). Excitation level of a stereo retina corresponding to a given axial local maximum (right). True tracks (stars), reconstructed track candidates (red dots), and truth-matched reconstructed track candidates (black dots)." numbered="true">}}

{{< figure src="performace_table.png" title="Axial only ($\epsilon_A$) and three-dimensional ($\epsilon_{AS}$) averaged reconstruction efficiencies fordifferent simulated samples and different track categories.  The ghost rate is also shown.  The downstream strange tracks are mainly pions from $K_0^S\to \pi^+\pi^-$decay." numbered="true">}}
