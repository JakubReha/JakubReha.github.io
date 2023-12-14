---
title: 'Anomaly Detection in Continuous-Time Temporal Provenance Graphs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Giulio Lovisotto
  - Michele Russo
  - Alessio Gravina
  - Claas Grohnfeldt

date: '2023-10-21T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-10-21T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: *Temporal Graph Learning Workshop @ NeurIPS 2023*
publication_short: *TGL NeurIPS 2023*

abstract: Recent advances in Graph Neural Networks (GNNs) have matured the field of learning on graphs, making GNNs essential for prediction tasks in complex, interconnected, and evolving systems. In this paper, we focus on self-supervised, inductive learning for continuous-time dynamic graphs. Without compromising generality, we propose an approach to learn representations and mine anomalies in provenance graphs, which are a form of large-scale, heterogeneous, attributed, and continuous-time dynamic graphs used in the cybersecurity domain, syntactically resembling complex temporal knowledge graphs. We modify the Temporal Graph Network (TGN) framework to heterogeneous input data and directed edges, refining it specifically for inductive learning on provenance graphs. We present and release two pioneering large-scale, continuous-time temporal, heterogeneous, attributed benchmark graph datasets. The datasets incorporate expert-labeled anomalies, promoting subsequent research on representation learning and anomaly detection on intricate real-world networks. Comprehensive experimental analyses of modules, datasets, and baselines underscore the effectiveness of TGN-based inductive learning, affirming its practical utility in identifying semantically significant anomalies in real-world systems.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [graph neural networks, temporal graphs, benchmark datasets, anomaly detection, heterogeneous graphs]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/forum?id=88tGIxxhsf'
url_code: 'https://github.com/JakubReha/ProvCTDG'
url_dataset: 'https://github.com/JakubReha/ProvCTDG'
url_poster: ''
url_project: ''
url_slides: ''
#uncomment
#url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
#uncomment
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Snapshot of a provenance graph cyber attack'
  focal_point: ''
  preview_only: false

projects:
   - example
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
 Create your slides in Markdown - click the _Slides_ button to check out the example.
 {{% /callout %}}


Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
