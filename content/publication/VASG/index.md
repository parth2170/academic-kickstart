---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Visually Aware Skip-Gram for Image Based Recommendations"
authors: ['Parth Tiwari', 'Yash Jain', 'Shivansh Mundra', 'Jenny Harding', 'Manoj Kumar Tiwari']
date: 2020-08-18T21:19:38+05:30
doi: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

abstract: "The visual appearance of a product significantly influences purchase decisions on e-commerce websites. We propose a novel framework VASG (Visually Aware Skip-Gram) for learning user and product representations in a common latent space using product image features. Our model is an amalgamation of the Skip-Gram architecture and a deep neural network based Decoder. Here the Skip-Gram attempts to capture user preference by optimizing user-product co-occurrence in a Heterogeneous Information Network while the Decoder simultaneously learns a mapping to transform product image features to the Skip-Gram embedding space. This architecture is jointly optimized in an end-to-end, multitask fashion. The proposed framework enables us to make personalized recommendations for cold-start products which have no purchase history. Experiments conducted on large real-world datasets show that the learned embeddings can generate effective recommendations using nearest neighbour searches."

# Summary. An optional shortened abstract.
summary: ""

tags: ['Recommender Systems', 'Skip-Gram', 'Representation Learning', 'Image Features', 'Heterogeneous Information Network']
categories: []
featured: true

url_pdf: "https://arxiv.org/abs/2008.06908"
url_code: "https://github.com/parth2170/triplet-recsys"
url_dataset: "http://jmcauley.ucsd.edu/data/amazon/"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "VASG Framework"
  focal_point: ""
  preview_only: false

commentable: true
share: false
---

