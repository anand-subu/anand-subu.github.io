---
title: 'A robust section identification method for scanned electronic health records'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Praveen Kumar Suresh
  - Sudarsun Santhiappan
  - 
date: '2023-01-04T00:00:00Z'
doi: '10.1145/3570991.3571011'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "In CODS-COMAD '23: Proceedings of the 6th Joint International Conference on Data Science & Management of Data (10th ACM IKDD CODS and 28th COMAD)"
publication_short: "In CODS-COMAD '23"

abstract: An Electronic Health Record (EHR) is a digital document containing critical information concerning a patient’s visit to a hospital. However, since they are often archived as scanned images, Optical Character Recognition (OCR) is used to extract the clinical text for analytics. The accuracy of OCR is compromised when the scanned EHRs contain noise artifacts or when the scans are of poor quality. Clinical text sections in the EHR help precisely locate information pertinent to a specific aspect of a patient’s visit, which is vital for any downstream clinical analytics activities such as medical coding, medical necessity assessment, and diagnosis identification. Section Identification is the task of identifying the different sections present in an EHR with the help of their headers. Traditionally, rule-based keyword matching and statistical approaches are employed to solve this problem. However, these approaches rely on external lookups and knowledge bases and are therefore susceptible to the errors introduced by OCR processes. We propose a character-based word sequence modeling approach for Clinical Section Identification from scanned EHRs that is robust against OCR-induced errors. We also utilize character augmentation techniques from existing literature to improve their robustness to OCR errors. We empirically demonstrate that our models trained with and without character augmentation significantly outperform existing approaches on a medical dataset with OCR errors.

# Summary. An optional shortened abstract.
summary: An Electronic Health Record (EHR) is a digital document containing critical information concerning a patient’s visit to a hospital. However, since they are often archived as scanned images, Optical Character Recognition (OCR) is used to extract the clinical text for analytics. The accuracy of OCR is compromised when the scanned EHRs contain noise artifacts or when the scans are of poor quality. Clinical text sections in the EHR help precisely locate information pertinent to a specific aspect of a patient’s visit, which is vital for any downstream clinical analytics activities such as medical coding, medical necessity assessment, and diagnosis identification. Section Identification is the task of identifying the different sections present in an EHR with the help of their headers. Traditionally, rule-based keyword matching and statistical approaches are employed to solve this problem. However, these approaches rely on external lookups and knowledge bases and are therefore susceptible to the errors introduced by OCR processes. We propose a character-based word sequence modeling approach for Clinical Section Identification from scanned EHRs that is robust against OCR-induced errors. We also utilize character augmentation techniques from existing literature to improve their robustness to OCR errors. We empirically demonstrate that our models trained with and without character augmentation significantly outperform existing approaches on a medical dataset with OCR errors.

tags: [Clinical NLP, Section Identification, OCR]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3570991.3571011'
url_poster: ''
url_project: ''
url_slides: content/publication/section_identification/cods_presentation.pdf
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
