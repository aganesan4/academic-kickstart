+++
title = "Redundancy Does Not Imply Fault Tolerance: Analysis of Distributed Storage Reactions to Single Errors and Corruptions"
date = 2017-03-01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Aishwarya Ganesan", "Ramnatthan Alagappan", "Andrea C. Arpaci-Dusseau", "Remzi H. Arpaci-Dusseau"]

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
publication = "In Proceedings of the 15th USENIX Conference on File and Storage Technologies"
publication_short = "FAST ’17"

# Abstract and optional shortened version.
abstract = "We analyze how modern distributed storage systems behave in the presence of file-system faults such as data corruption and read and write errors. We characterize eight popular distributed storage systems and uncover numerous bugs related to file-system fault tolerance. We find that modern distributed systems do not consistently use redundancy to recover from file-system faults: a single file-system fault can cause catastrophic outcomes such as data loss, corruption, and unavailability. Our results have implications for the design of next generation fault-tolerant distributed and cloud storage systems."
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
url_pdf = "http://research.cs.wisc.edu/adsl/Publications/fast17-ganesan.pdf"
url_preprint = ""
url_code = "https://github.com/aganesan4/CORDS"
url_dataset = ""
url_project = "http://research.cs.wisc.edu/adsl/Software/cords/"
url_slides = "http://research.cs.wisc.edu/adsl/Publications/fast17-aishwarya-slides.pdf"
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "bibtex", url = "http://research.cs.wisc.edu/adsl/Publications/cords-fast17.bib"}]

press_urls = [{name = "morning paper blog", url = "https://blog.acolyer.org/2017/03/08/redundancy-does-not-imply-fault-tolerance-analysis-of-distributed-storage-reactions-to-single-errors-and-corruptions/"}, {name = "StorageMojo", url = "https://storagemojo.com/2017/03/01/storagemojos-best-paper-of-fast-2017/"}]

awards = ["Best Paper Award Nominee"]

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

#{{< tweet 839471405796319232 >}}
#{{< tweet 839393002158194692 >}}
#{{< tweet 839518601078001664 >}}
#{{< tweet 839441480460734465 >}}