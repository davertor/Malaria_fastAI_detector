![Made-love][made-love-shield]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Malaria_fastAI_detector
[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OpIIpDUA-M9QD-PExdYzXY3FJ8qG3l9i?usp=sharing)

Notebook of a fastAI implementation of a Malaria detector.

![Coloring result][product-screenshot]

## Description
Malaria is a mosquito-borne infectious disease that affects humans, which can cause coma or death in several cases if it is not properly treated. Approximately 93% of the cases and 94% of deaths occurred in Africa, where the healthcare system is very deficient due to the lack of resources.

There are several methods and tests which can be used for malaria detection. Microscopic examination of blood is the best known method for diagnosis, but it is a very slow method because a trained technician has to manually examine around 5000 cells and count how many cells has a parasite inside them. Therefore, this is the point where AI can make the difference by building an automatic malaria classification system.

Today, I bring a FastAI implementation of a Malaria detector, with the goal of reproducing state-of-art results (97% precision), using FastAi library instead of Keras, which was the one proposed in the original paper. The results of my training were a precision of 98% over the test set of images using a ResNet-50 model, and a 97% precision with a ResNet-18, which offers best tradeoff for using it in mobile devices.

## Instructions
For working with this notebook, clone repo and execute it in your favourite Notebook environment, or open Google's colab and introduce the following link: https://github.com/davertor/Malaria_fastAI_detector

## References
* [Malaria Wiki](https://en.wikipedia.org/wiki/Malaria )
* [Malaria webapp detector](https://blog.insightdatascience.com/https-blog-insightdatascience-com-malaria-hero-a47d3d5fc4bb)

## Contact
* [@davertor](https://github.com/davertor) 

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: images/data_input.png
[linkedin-url]: https://linkedin.com/daniel-verdu-torres

[made-love-shield]: https://img.shields.io/badge/-Made%20with%20love%20❤️-orange.svg?style=for-the-badge
[license-shield]: https://img.shields.io/badge/License-GNU-brightgreen.svg?style=for-the-badge
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-darkblue.svg?style=for-the-badge&logo=linkedin
[twitter-shield]: https://img.shields.io/badge/-Twitter-blue.svg?style=for-the-badge&logo=twitter

