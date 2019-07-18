+++
title = " On latent position inference from doubly stochastic messaging activities"
date = 2013-07-31T12:08:31-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Nam H. Lee", "Jordan Yoder", "Minh Tang", "Carey E. Priebe"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Multiscale Modeling and Simulation"
publication_short = ""

# Abstract and optional shortened version.
abstract = "We model messaging activities as a hierarchical doubly stochastic point process with three main levels and develop an iterative algorithm for inferring actors’ relative latent positions from a stream of messaging activity data. Each of the message-exchanging actors is modeled as a process in a latent space. The actors’ latent positions are assumed to be influenced by the distribution of a much larger population over the latent space. Each actor’s movement in the latent space is modeled as being governed by two parameters that we call confidence and visibility, in addition to dependence on the population distribution. The messaging frequency between a pair of actors is assumed to be inversely proportional to the distance between their latent positions. Our inference algorithm is based on a projection approach to an online filtering problem. The algorithm associates each actor with a probability density-valued process, and each probability density is assumed to be a mixture of basis functions. For efficient numerical experiments, we further develop our algorithm for the case where the basis functions are obtained by translating and scaling a standard Gaussian density."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://epubs.siam.org/doi/abs/10.1137/120878896"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

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
