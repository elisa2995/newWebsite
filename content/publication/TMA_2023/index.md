---
title: 'Towards Detecting and Geolocalizing Web Scrapers with Round Trip Time Measurements'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Marc Dacier
  - Olivier Thonnard


date: '2023-06-30T00:00:00Z'
doi: '10.23919/TMA58422.2023.10199089'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *7th IFIP Network Traffic Measurement and Analysis Conference (TMA 2023)*
publication_short: In *TMA 2023*

abstract: Many websites in different domains suffer from the large number of requests originated by web scraping. Hence, these websites exploit detection mechanisms to try to block scrapers' requests. Lately, scrapers evade more and more these mechanisms by hiding behind the so-called Residential IP Proxies (RESIP). We have created a server-side detection method, based on network measurements, that enables us to detect whether a request passes through one of these providers. We have run a 4-month long experiment to assess the validity of our technique and we have collected a 90M+ connections dataset. In this work, we present new analyses performed on this dataset. They show that our detection technique can work in any real-world environment and that has a good level of accuracy even in the unlikely event where client, server and RESIP machines are all in close proximity. Moreover, we introduce the next steps in our research. We implemented our detection technique in front of domains suffering from web scraping. The study of these connections is ongoing. Furthermore, we are implementing an algorithm to geolocalize the scrapers behind the RESIP, thanks to network measurements on their connections.
# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://github.com/elisa2995/elisa2995.github.io/raw/main/papers/Chiapponi_Towards_2023.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: 'https://github.com/elisa2995/elisa2995.github.io/raw/main/papers/Chiapponi_Towards_Poster_2023.pdf'
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
