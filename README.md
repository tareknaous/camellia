# Camellia: Benchmarking Cultural Biases in LLMs for Asian Languages

This repository contains the entities and masked contexts of the Camellia dataset for measuring entity-centric cultural biases in LLMs for Asian languages.

The benchmark covers 9 Asian languages  (```Chinese, Japanese, Korean, Vietnamese, Urdu, Hindi, Gujarati, Marathi, Malayalam```) and 6 Asian cultures (```Chinese, Japanese, Korean, Vietnamese, Pakistani, Indian```).

For more details, see the accompanying paper:

[Camellia: Benchmarking Cultural Biases in LLMs for Asian Languages](https://arxiv.org/pdf/2510.05291), **arXiv 2025**

## Cultural Entities

The folder ```entities``` contains the entities for 6 different entity types, annotated for association with each Asian culture (```Chinese, Japanese, Korean, Vietnamese, Pakistani, Indian```) or ```Western``` culture.

## Masked Contexts

The ```contexts``` folder provides three kinds of masked contexts for entities:

- ```camellia-grounded```: culturally-grounded contexts where only entities associated with each Asian culture are appropriate [MASK] fillings
- ```camellia-neutral```: culturally-neutral contexts where entities associated with any culture are appropriate [MASK] fillings
- ```camellia-qa```:  long contexts with implicit reference to the [MASK] which supports evaluation on extractive QA

All contexts and entities are paired with an English translation.

 
## Citation
```
@misc{naous2025camelliabenchmarkingculturalbiases,
      title={Camellia: Benchmarking Cultural Biases in LLMs for Asian Languages}, 
      author={Tarek Naous and Anagha Savit and Carlos Rafael Catalan and Geyang Guo and Jaehyeok Lee and Kyungdon Lee and Lheane Marie Dizon and Mengyu Ye and Neel Kothari and Sahajpreet Singh and Sarah Masud and Tanish Patwa and Trung Thanh Tran and Zohaib Khan and Alan Ritter and JinYeong Bak and Keisuke Sakaguchi and Tanmoy Chakraborty and Yuki Arase and Wei Xu},
      year={2025},
      eprint={2510.05291},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2510.05291}, 
} 
```

## Contact
**Tarek Naous**: [Scholar](https://scholar.google.com/citations?user=ImyLv44AAAAJ&hl=en) | [Github](https://github.com/tareknaous?tab=repositories) |
[Linkedin](https://www.linkedin.com/in/tareknaous/) |  [Research Gate](https://www.researchgate.net/profile/Tarek_Naous?ev=hdr_xprf) | [Personal Wesbite](https://tareknaous.github.io/)
| tareknaous@gatech.edu


