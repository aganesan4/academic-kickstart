+++
title = "Protocol-Aware Recovery for Consensus-Based Storage"
date = 2018-02-11
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ramnatthan Alagappan", "Aishwarya Ganesan", "Eric Lee", "Aws Albarghouthi", "Vijay Chidambaram",
"Andrea C. Arpaci-Dusseau", "Remzi H. Arpaci-Dusseau"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In Proceedings of the 16th USENIX Conference on File and Storage Technologies"
publication_short = "FAST ’18"

# Abstract and optional shortened version.
abstract = "We introduce protocol-aware recovery (PAR), a new approach that exploits protocol-specific knowledge to correctly recover from storage faults in distributed systems. We demonstrate the efficacy of PAR through the design and implementation of corruption-tolerant replication (CTRL), a PAR mechanism specific to replicated state machine (RSM) systems. We experimentally show that the CTRL versions of two systems, LogCabin and ZooKeeper, safely recover from storage faults and provide high availability, while the unmodified versions can lose data or become unavailable. We also show that the CTRL versions have little performance overhead."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
#tags = [""]

# Links (optional).
url_pdf = "http://research.cs.wisc.edu/adsl/Publications/par-ctrl-fast18.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "http://research.cs.wisc.edu/adsl/Publications/fast18-ram-slides.pdf"
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "bibtex", url = "http://research.cs.wisc.edu/adsl/Publications/par-ctrl-fast18.bib"}]

press_urls = [{name = "morning paper blog", url = "https://blog.acolyer.org/2018/02/27/protocol-aware-recovery-for-consensus-based-storage/"}, {name = "zdnet", url = "https://www.zdnet.com/article/eliminating-storage-failures-in-the-cloud/"}]


awards = ["Best Paper Award"]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""
+++
