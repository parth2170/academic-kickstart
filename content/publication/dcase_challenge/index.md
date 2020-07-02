---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Modulation Spectrums and i-Vectors for Anomalous Sound Detection"
authors: ['Parth Tiwari', 'Yash Jain', 'Anderson Avila', 'Joao Monteiro', 'Shruti Kshirsagar', 'Amr Gaballah', 'Tiago H. Falk']
date: 2020-07-01T21:19:38+05:30
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

abstract: "In this paper, we propose two different anomalous sound detection systems, one based on features extracted from a modulation spectral signal representation and the other based on i-vectors extracted from mel-band features. The first system uses a nearest neighbour graph to construct clusters which capture local variations in the training data. Anomalies are then identified based on their distance from the cluster centroids. The second system uses i-vectors extracted from mel-band spectra for training a Gaussian Mixture Model. Negative log-likelihood values are then used as anomaly scores. Both systems have been submitted to Task-2 of the DCASE 2020 Challenge and show significant improvement over the baseline AUC scores, with an average improvement of 6% across all machines. An ensemble of the two systems is shown to further improve the average performance by 11% over the baseline."

# Summary. An optional shortened abstract.
summary: ""

tags: ['Anomaly Detection', 'Signal Processing']
categories: []
featured: true

url_pdf: "http://dcase.community/documents/challenge2020/technical_reports/DCASE2020_Tiwari_84_t2.pdf"
url_code: "https://github.com/parth2170/DCASE2020-Task2.git"
url_dataset: "http://dcase.community/challenge2020/task-unsupervised-detection-of-anomalous-sounds"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Modulation Spectrum Representations"
  focal_point: ""
  preview_only: false

commentable: true
share: false
---

