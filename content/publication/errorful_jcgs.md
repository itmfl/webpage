+++
title = "Statistical inference on errorfully observed graphs"
date = 2015-12-31T11:33:11-04:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Carey E. Priebe", "Daniel L. Sussman", "Minh Tang", "Joshua T. Vogelstein"]

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
publication = "Journal of Computational Graphical Statistics"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Statistical inference on graphs is a burgeoning field in the applied and theoretical statistics communities, as well as throughout the wider world of science, engineering, business, etc. In many applications, we are faced with the reality of errorfully observed graphs. That is, the existence of an edge between two vertices is based on some imperfect assessment. In this paper, we consider a graph $G=(V,E)$. We wish to perform an inference task---the inference task considered here is \"vertex classification\". However, we do not observe $G$; rather, for each potential edge $uv \\in \\tbinom{V}{2}$ we observe an \"edge-feature\" which we use to classify $uv$ as edge/not-edge. Thus we errorfully observe $G$ when we observe the graph $\\tilde{G}=(V,\\tilde{E})$ as the edges in $\\tilde{E}$ arise from the classifications of the \"edge-features\", and are expected to be errorful. Moreover, we face a quantity/quality trade-off regarding the edge-features we observe --- more informative edge-features are more expensive, and hence the number of potential edges that can be assessed decreases with the quality of the edge-features. We studied this problem by formulating a quantity/quality tradeoff for a simple class of random graphs model, namely the stochastic blockmodel. We then consider a simple but optimal vertex classifier for classifying $v$ and we derive the optimal quantity/quality operating point for subsequent graph inference in the face of this trade-off. The optimal operating points for the quantity/quality trade-off are surprising and illustrate the issue that methods for intermediate tasks should be chosen to maximize performance for the ultimate inference task. Finally, we investigate the quantity/quality tradeoff for errorful obesrvations of the *C.elegans* connectome graph."
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
url_pdf = "https://doi.org/10.1080/10618600.2014.951049"
url_preprint = "https://arxiv.org/abs/1211.3601"
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
