+++

title = "A Model Output Deep Learning Method for Grid Temperature Forecasts in Tianjin Area"
date = 2020-03-05T00:00:00
draft = false

# Authors. Comma separated list, e.g. ["Bob Smith", "David Jones"].
authors = ["Keran Chen", "Ping Wang", "Xiaojuan Yang", "Nan Zhang", "Di Wang*"]

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
publication = "*Applied Sciences*, 2020."
publication_short = "*Applied Sciences*"

# Abstract and optional shortened version.
abstract = "In weather forecasting, numerical weather prediction (NWP) that is based on physical models requires proper post-processing before it can be applied to actual operations. Therefore, research on intelligent post-processing algorithms has always been an important topic in this field. This paper proposes a model output deep learning (MODL) method for post-processing, which can improve the forecast effect of numerical weather prediction. MODL is an end-to-end post-processing method based on deep convolutional neural network, which directly learns the mapping relationship between the forecast fields output by numerical model and the observation temperature field in order to obtain more accurate temperature forecasts. MODL modifies the existing deep convolution model according to the post-processing problem’s characteristics, thereby improving the performance of the weather forecast. This paper uses The International Grand Global Ensemble (TIGGE) dataset from European Centre for Medium-Range Weather Forecasts (ECMWF) and the observed air temperature of 2 m obtained from Tianjin meteorological station in order to test the post-processing performance of MODL. The MODL method applied to temperature in post-processing is compared with the ECMWF forecast, Model Output Statistics (MOS) methods, and Model Output Machine Learning (MOML) methods. The Root Mean Square Error (RMSE) of the temperature field predicted by MODL and the observed temperature field is smaller than the other models and the accuracy of the temperature difference of 2 °C (Acc) is higher, especially where the prediction time is in the first three days. The lightweight nature of MODL also makes it suitable for most operations."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
# Associate this publication with one or more of your projects.
# Simply enter your project's folder or file name without extension.
# E.g. projects = ["deep-learning"] references
# content/project/deep-learning/index.md.
# Otherwise, set projects = [].
projects = []

# Slides (optional).
# Associate this publication with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. slides = "example-slides" references
# content/slides/example-slides.md.
# Otherwise, set slides = "".
slides = ""

# Tags (optional).
# Set tags = [] for no tags, or use the form tags = ["A Tag", "Another Tag"] for one or more tags.
tags = ["Numerical Weather Prediction"]

# Links (optional).
url_pdf = "https://www.mdpi.com/2076-3417/10/17/5808/htm"
url_code = "https://www.mdpi.com/2076-3417/10/17/5808/htm"
#url_dataset = ""
#url_project = ""
#url_slides = ""
#url_video = ""
#url_poster = ""
#url_source = ""

# Custom links (optional).
# Uncomment line below to enable. For multiple links, use the form [{...}, {...}, {...}].
# url_custom = [{name = "Custom Link", url = "http://example.org"}]
# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named featured.jpg/png to your page's folder.

#[image]  
  # Caption (optional)
  #caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  #focal_point = "

+++
