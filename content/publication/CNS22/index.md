---
title: 'Generalizable perceptual embedding with noise-tuning alignment'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jungwon Ryu
  - admin
  - Sang Wan Lee

# Author notes (optional)

date: '2022-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']


# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 31st Annual Computational Neuroscience Meeting (CNS)"
publication_short: "CNS 2022"

abstract: "Our perception of the external world is always limited and ambiguous, and the activities of sensory neurons are inherently noisy. Such exogenous and endogenous uncertainty factors pose a fundamental challenge for sensory coding. Despite the earlier studies for understanding how biological vision resolves these issues, little is known about how it can learn accurate and generalizable representations.

Two prominent computational approaches include identifying the underlying statistical regularities across the stimuli via dimensionality reduction and developing the model that encodes the stimulus probabilistically.

Here, adopting the perspective of the well-known requisite variety principle, we investigated the effect of the encoded uncertainty on the statistical structure of the stimuli that the model has learned. Specifically, we tested whether and how the global geometrical distribution of the latent variables is aligned with the local latent probability distribution that encodes the input stimulus. For this, we present a new computational model accommodating the noise-tuning alignment, which auto-encodes the input stimuli using the conditional latent distributions (Fig. a). We defined the tuning and noise covariances as the means and the covariances of the latent distributions, which specify the local manifold in the latent space for the given input. Whereas the tuning covariance is defined as the covariances of the tunings for the given mini-batch of stimuli, capturing the global structure of the latent manifold. Then we tested whether and how the local and global manifolds are aligned, and investigated their relationship with the generalization performance in image reconstruction tasks.

Simulations with three real-world benchmark datasets revealed that our models outperformed baseline probabilistic models such as variational autoencoders (Fig. b). To understand the learned noise covariance structure, we first computed the correlations between the noise covariances and the tuning similarity of the latent variable pairs. Interestingly, we found that the learning process of our model encourages non-negative correlation, as is often found in the primate visual cortex [1], but not in VAE models (Fig. c). When measuring the alignment angle between the tuning covariance and noise covariance, we found that two subspaces are more strongly aligned in our model, such that the primary noise principal components (PC) are more aligned with the primary tuning PC that explains stimulus variability, consistent with the recent single-cell studies [2]. On the contrary, these patterns were not identified in VAEs (Fig. d). Further, we found the amount of alignment is negatively correlated with the generalization error across datasets and models (Fig. e), and even within each model (Fig. f). Our findings suggest that noise-tuning alignment helps the stimulus generalization, expanding the current understanding of the correlated neuronal noise [3–5].
"

# Summary. An optional shortened abstract.
summary: "In proceedings of the 31st Annual Computational Neuroscience Meeting (CNS), 2022"

tags: []
categories: []
# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
projects:
  - ''

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
