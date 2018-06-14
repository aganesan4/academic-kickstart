+++
title = "Correlated Crash Vulnerabilities"
date = 2016-11-01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ramnatthan Alagappan", "Aishwarya Ganesan", "Yuvraj Patel" , "Thanumalayan Sankaranarayana Pillai", "Andrea C. Arpaci-Dusseau", "Remzi H. Arpaci-Dusseau"]

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
publication = "In Proceedings of the 12th Symposium on Operating System and Design Implementation"
publication_short = "OSDI '16"

# Abstract and optional shortened version.
abstract = "Modern distributed storage systems employ complex protocols to update replicated data. In this paper, we study whether such update protocols work correctly in the presence of correlated crashes. We find that the correctness of such protocols hinges on how local filesystem state is updated by each replica in the system. We build PACE, a framework that systematically generates and explores persistent states that can occur in a distributed execution. PACE uses a set of generic rules to effectively prune the state space, reducing checking time from days  o hours in some cases. We apply PACE to eight widely used distributed storage systems to find correlated crash vulnerabilities, i.e., problems in the update protocol that lead to user-level guarantee violations. PACE finds a total of 26 vulnerabilities across eight systems, many of which lead to severe consequences such as data loss, corrupted data, or unavailable clusters."
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
url_pdf = "http://research.cs.wisc.edu/adsl/Publications/ram-osdi16.pdf"
url_preprint = ""
url_code = "https://github.com/ramanala/PACE"
url_dataset = ""
url_project = ""
url_slides = "https://www.usenix.org/sites/default/files/conference/protected-files/osdi16_slides_alagappan.pdf"
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "bibtex", url = "http://research.cs.wisc.edu/adsl/Publications/pace-osdi16.bib"}]

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
