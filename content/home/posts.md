+++
# A Recent Blog Posts section created with the Pages widget.

# This section displays recent blog posts from `content/post/`.

widget = "pages"  
# Do not modify this line!
active = false  
# Activate this widget? true/false
weight = 40  
# Order that this section will appear.

title = "Recent Posts Go Here"
subtitle = ""

[content]
  
# Page type to display. E.g. post, talk, or publication.
  page_type = "publication"
  
  
# Choose how much pages you would like to display (0 = all pages)
  count = 5
  
  
# Choose how many pages you would like to offset by
  offset = 0

  
# Page order. Descending (desc) or ascending (asc) date.
  order = "desc"

  
# Filter posts by a taxonomy term.
  [content.filters]
    tag = ""
    category = ""
    publication_type = ""
    exclude_featured = false
  
[design]
  
# Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view = 2
  
[design.background]
  
# Apply a background color, gradient, or image.
  
#   Choose a light or dark text color by setting `text_color_light`.
  
#   Any HTML color name or Hex value is valid.
  
  
# Background color.
  # color = "navy"
  
  
# Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  
# Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  
# Text color (true=light or false=dark).
  text_color_light = false  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""  

+++title = "{{ replace .Name "-" "Title " |title }}" 
date = {{ .Date }}


# Authors Comma separated list, eg `["Bob Smith", "David Jones"]`.
authors = ["Barbosa", "Bilan", "Celerier"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["0"]

# Publication name and optional abbreviated version.
publication = ""
publication_short = ""

# Abstract.
abstract = ""

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
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
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
