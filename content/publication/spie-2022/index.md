---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Evaluation of the impact of physical adversarial attacks on deep learning models for classifying covid cases"
authors: 
 - Erikson Aguiar 
 - Karem Marcomini 
 - Felipe Quirino 
 - Marco Gutierrez
 - Caetano Traina Jr 
 - Agma Traina
date: 2022-03-27T15:04:52-03:00
doi: "10.1117/12.2611199"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-27T15:04:52-03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings Volume 12033, Medical Imaging 2022: Computer-Aided Diagnosis"
publication_short: "SPIE Medical Imaging, 2022"

abstract: "The SARS-CoV-2 (COVID-19) disease rapidly spread worldwide, thus increasing the need to create new strategies to fight it. Several researchers in different fields have attempted to develop methods to early identifying it and mitigating its effects. The Deep Learning (DL) approach, such as the Convolutional Neural Networks (CNNs), has been increasingly used in COVID-19 diagnoses. These models intend to support decision-making and are doing well to detecting patient status early. Although DL models have good accuracy to support diagnosis, they are vulnerable to Adversarial Attacks. These attacks are new methods to make DL models biased by adding small perturbations on the original image. This paper investigates the impact of Adversarial Attacks on DL models for classifying X-ray images of COVID-19 cases. We focused on the attack Fast Gradient Sign Method (FGSM), which aims to add perturbations to the testing images by combining a perturbation matrix, producing a crafted image. We conduct the experiments analyzing the model’s performance attack-free and adding attacks. The following CNNs models were selected: DenseNet201, ResNet-50V2, MobileNetV2, NasNet and VGG16. In the attack-free environment, we reach precision around 99%. When it adds the attack, our results revealed that all models suffer from performance reduction, and the most affected was MobileNet that reduced its ability from 98.61% to 67.73%. However, the VGG16 network showed to be the least affected by the attacks. Our finds describe that DL models for COVID-19 are vulnerable to Adversarial Examples. The FGSM was capable of fooling the model, resulting in a significant reduction in the DL performance."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://doi.org/10.1117/12.2611199
# url_code:
# url_dataset:
# url_poster:
# url_project:
# url_slides:
# url_source:
# url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
# image:
#   caption: ""
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
