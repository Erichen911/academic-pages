+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Post-processing of medium-term numerical weather prediction based on deep learning methods"
  date_start = "2019-10"
  date_end = "present"
  description = """
  NWP is a three-dimensional weather forecast tensor with temporal and spatial information in European space. My research is to use a 3D fully convolutional network to improve forecast accuracy.  
  * Improve the Focal loss method to solve the sample imbalance of precipitation data.
  * Connect a discriminator network after fully convolutional network to improve wind direction similarity.
  * Construct a U-net structure network to improve the accuracy of the forecast.
  * Connect a constructive learning method to improve the accuracy of visibility and total cloud cover.
  """

[[experience]]
  title = "Professor"
  company = "University X"
  company_url = ""
  location = "California"
  date_start = "2016-01-01"
  date_end = "2016-12-31"
  description = """Taught electronic engineering and researched semiconductor physics."""

+++
