---
title: 'Exploring Deep Learning Based Approaches for Endoscopic Artefact Detection and Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Mukesh Reghu
  - Sriram Rajkumar
  
date: '2021-12-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-shared-task']

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of the 18th International Conference on Natural Language Processing: Shared Task on Multilingual Gender Biased and Communal Language Identification"
publication_short: "In ComMA@ICON 2021"

abstract: The Endoscopic Artefact Detection challenge comprises tasks for detection and segmentation of artefacts found in endoscopic imaging, with a specific task for evaluating the generalization capacity of detection algorithms on external data. For the detection of artefacts, we train RetinaNet and FasterRCNN models. To segment artefacts from the endoscopic images, we train a Deeplab v3 model and a U-Net model and also implement post-processing techniques such as the usage of an EAST text detector for detection of text artefacts and pixel-wise voting ensemble after applying test time augmentation. We observe that the RetinaNet model with a ResNet101 feature extractor is the best performing model across all object detection tasks, while the U-Net performs best in the segmentation tasks. We also implement a model agnostic object tracking pipeline utilizing image correlation-based trackers to reduce the inference time of object detection models. We believe that this pipeline can enable real-time analysis of endoscopic images in systems with processing constraints.

# Summary. An optional shortened abstract.
summary: This paper details our submission to the Endoscopic Artefact Detection challenge held as part of EndoCV at ISBI 2020. We experiment with various deep-learning based solutions for artefact detection and segmentation.

tags: [Medical Imaging, Endoscopic Imaging, Object Detection]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ceur-ws.org/Vol-2595/endoCV2020_paper_id_22.pdf'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
