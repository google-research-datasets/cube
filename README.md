# Beyond Aesthetics: Cultural Competence in Text-to-Image Models


**Contents of this repsository has been moved to https://github.com/google-deepmind/cube. Further updates will be made there.**

This repository contains data resources for the paper: [Beyond Aesthetics: Cultural Competence in Text-to-Image Models](https://www.arxiv.org/abs/2407.06863). It contains cultural artifacts across 8 countries (Brazil, France, India, Italy, Japan, Nigeria, Turkey, and USA) and 3 domains (cuisine, landmarks, art). 

The dataset is divided into two parts:
1. **CUBE-CSpace**: a collection of 300k cultural artifacts, intended to be used as grounding for diversity evaluation. For example,
* Japanese Cuisine: Ramen, Soba, Sushi, Katsu sandwich
* France Landmarks: Eiffel Tower, Mont Saint-Michel, Palace of Versailles
* Indian Art/Clothing: Kurta, Lehanga Choli, Dhoti, Patola Saree

2. **CUBE-1K**: a curated set of 1000 prompts constructed from cultural artifacts in CUBE-CSpace, that enable evaluation of cultural awareness. For example,
* Cuisine: A high resolution image of sushi from Japanese cuisine.
* Landmarks: A panoramic view of Eiffel Tower in France.
* Art: Clothing Image of a person in kurta from India.

 ## Citing this work
```
@misc{kannen2024aestheticsculturalcompetencetexttoimage,
      title={Beyond Aesthetics: Cultural Competence in Text-to-Image Models}, 
      author={Nithish Kannen and Arif Ahmad and Marco Andreetto and Vinodkumar Prabhakaran and Utsav Prabhu and Adji Bousso Dieng and Pushpak Bhattacharyya and Shachi Dave},
      year={2024},
      eprint={2407.06863},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2407.06863}, 
}
```

## License
We distribute CUBE under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en) license 

*This is not an officially supported Google product.*
