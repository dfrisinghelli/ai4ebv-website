+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "Project background"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  # text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

## Motivation

The Group on Earth Observations Global Network for Observations and Information in Mountain Environments, [GEO Mountains](https://bioone.org/journals/mountain-research-and-development/volume-38/issue-3/MRD-JOURNAL-D-8-00065.1/Monitoring-Mountains-in-a-Changing-World--New-Horizons-for/10.1659/MRD-JOURNAL-D-8-00065.1.full), is a GEO Work Programme Initiative that seeks to connect and facilitate access to diverse sources of mountain observation data and information at different scales. At a recent GEO Mountains [workshop](https://mountainresearchinitiative.org/news-page-all/129-mri-news/2572-selecting-essential-biodiversity-variables-and-essential-societal-variables-for-mountains), experts on mountain ecosystems were convened to identify and prioritize [Essential Biodiversity Variables](https://geobon.org/ebvs/what-are-ebvs/) (EBVs) that are considered relevant for mountains, using the [GEO BON](https://geobon.org/) EBV framework as a starting point. For the EBV class on Ecosystem Structure, the EBVs *Ecosystem extent* and *Ecosystem fragmentation* were identified as priorities to monitor and better understand changes in mountain ecosystems and their species-level biodiversity. Both EBVs require the mapping of ecosystem occurrences and ecosystem distributions to determine the area occupied by ecosystems (Ecosystem Extent) and how and where those areas are reduced due to natural and human-caused disturbances (Ecosystem Fragmentation).

**AI4EBV** aims to use Artificial Intelligence (AI) to derive accurate, high-resolution maps of mountain ecosystem extents by exploiting both the advanced  feature extraction capabilities provided by AI-based algorithms and the computational power of cloud-based platforms. Via the incorporation of the latest Earth observation data, we seek to produce these maps through time, thereby enabling a comprehensive assessment of ecosystem change and fragmentation.

## Research questions

The project makes use of the World Terrestrial Ecosystems (WTE) map that was recently produced by [Sayre et al. (2020)](https://www.sciencedirect.com/science/article/pii/S2351989419307231?via%3Dihub) at a spatial scale of 250 m. While the WTEs map offers a unique spatial representation of terrestrial ecosystems, several open questions regarding its utility for a broad range of stakeholders remain:

1. How accurate is the map of ecosystems for mountain regions?
2. Can high-resolution Earth observation data be used to improve the spatial resolution and thematic content of the WTE map?
3. Can the WTE map be updated based on Earth observation data?

