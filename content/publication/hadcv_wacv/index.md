---
title: 'Exploring Techniques to Improve Activity Recognition using Human Pose Skeletons'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bharath Raj N
  - admin
  - Kashyap Ravichandran
  - N. Venkateswaran
  
date: '2020-03-01T00:00:00Z'
doi: '10.1109/WACVW50321.2020.9096918'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-workshop']

# Publication name and optional abbreviated publication name.
publication: "In Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) Workshops, 2020"
publication_short: "In HADCV@WACV 2020"

abstract: Human pose skeletons provide an explainable representation of the orientation of a person. Neural network architectures such as OpenPose can estimate the 2D human pose skeletons of people present in an image with good accuracy. Naturally, the human pose is a very attractive choice as a representation for building systems aimed at human activity recognition. However, raw pose keypoint representations suffer from various problems such as variance to translation and scale of the input images. Keypoints are also often missed by the pose estimation framework. These, and other factors lead to poor generalization and learning of networks that may be trained directly on these raw representations. This paper introduces various methods aimed at building a robust representation for training models related to activity recognition tasks, such as the usage of handcrafted features extracted from poses with the intent of introducing scale and translation invariance. Additionally, the usage of train-time techniques such as keypoint dropout are explored to facilitate better learning of models. Finally, we conduct an ablation study comparing the performance of deep learning models trained on raw keypoint representation and handcrafted features whilst incorporating our train-time techniques to quantify the effectiveness of our introduced methods over raw representations.

# Summary. An optional shortened abstract.
summary: 

tags: [Human Activity Recognition, Pose Keypoint Representation, Pose Tracking]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content_WACVW_2020/papers/w5/N._Exploring_Techniques_to_Improve_Activity_Recognition_using_Human_Pose_Skeletons_WACVW_2020_paper.pdf'
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