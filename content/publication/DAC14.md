+++
title = "Balancing Scalability and Uniformity in SAT-Witness Generator "
date = 2014-06-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = [ "Supratik Chakraborty", "Kuldeep S. Meel","Moshe Y. Vardi"]

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
publication = "In *Proceedings of Design Automation Conference (DAC)*"


# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]


# Links (optional).
url_pdf = "http://www.comp.nus.edu.sg/~meel/Papers/DAC2014.pdf"
#url_preprint = ""
url_code = "https://bitbucket.org/kuldeepmeel/unigen/src/master/"
#url_dataset = ""
#url_project = ""
url_slides = "files/slides/DAC-Talk-June 03.pdf"
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
abstract = "Constrained-random simulation is the predominant approach used in the industry for functional verification of complex digital designs. The effectiveness of this approach depends on two key factors: the quality of constraints used to generate test vectors, and the randomness of solutions generated from a given set of constraints. In this paper, we focus on the second problem, and present an algorithm that significantly improves the state-of-the-art of (almost-)uniform generation of solutions of large Boolean constraints. Our algorithm provides strong theoretical guarantees on the uniformity of generated solutions and scales to problems involving hundreds of thousands of variables."

+++
