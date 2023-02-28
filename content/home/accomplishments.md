---
# An instance of the Accomplishments widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: accomplishments

# Activate this widget? true/false
active: true

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

# Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
title: 'Courses' #'Accomplish&shy;ments'
subtitle:

# Date format
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
item:
- certificate_url: #https://faculty.sist.shanghaitech.edu.cn/chenjh/courses/example/
  date_end: "2023-06-15"
  date_start: "2023-02-07"
  description: "Modeling and control of ac machines. Students are gonna get their hands dirty by learning programming along the way."
  organization: "Graduate/undergraduate (SIST Curriculum)"
  organization_url: "https://sist.shanghaitech.edu.cn/sist_en/3905/list.htm"
  title: EE275 Motor and motion control
  url: "https://faculty.sist.shanghaitech.edu.cn/chenjh/courses/example/"
# - certificate_url: https://www.edx.org
#   date_end: ""
#   date_start: "2021-01-01"
#   description: Formulated informed blockchain models, hypotheses, and use cases.
#   organization: edX
#   organization_url: https://www.edx.org
#   title: Blockchain Fundamentals
#   url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
# - certificate_url: https://www.datacamp.com
#   date_end: "2020-12-21"
#   date_start: "2020-07-01"
#   description: ""
#   organization: DataCamp
#   organization_url: https://www.datacamp.com
#   title: 'Object-Oriented Programming in R'
#   url: ""

design:
  columns: "2"
  background:
    image: slice-motor-24slots-prototype.jpg
    # imagefile: "slice-motor-24slots-prototype.jpg"
    # {{< staticref "uploads/slice-motor-24slots-prototype.jpg">}}
    image_darken: 0.2
    image_parallax: true
    image_position: center
    image_size: cover
    text_color_light: true
  # spacing:
  #   padding: ["200px", "0", "20px", "0"]
---
