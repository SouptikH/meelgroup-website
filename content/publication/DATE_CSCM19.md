+++
title = "BOSPHORUS: Bridging ANF and CNF Solvers "
date = 2019-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Davin Choo"," Mate Soos", "Kian Ming A. Chai", "Kuldeep S. Meel"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *Proceedings of Design, Automation, and Test in Europe (DATE)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "https://www.comp.nus.edu.sg/~meel/Papers/date-cscm19.pdf"
#url_preprint = ""
url_code = "https://github.com/meelgroup/bosphorus"
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = ""
#url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"



+++
abstract = "Algebraic Normal Form (ANF) and Conjunctive Normal Form (CNF) are commonly used to encode problems in Boolean algebra. ANFs are typically solved via Gr"obner basis algorithms, often using more memory than is feasible; while CNFs are solved using SAT solvers, which cannot exploit the algebra of polynomials naturally. We propose a paradigm that bridges between ANF and CNF solving techniques: the techniques are applied in an iterative manner to learn facts to augment the original problems. Experiments on over 1,100 benchmarks arising from four different applications domains demonstrate that learnt facts can significantly improve runtime and enable more benchmarks to be solved. "