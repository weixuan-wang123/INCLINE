<div align="center">
<h1>
Inference-Time Cross-Lingual Intervention (INCLINE)
</h1>
</div>

This repository contains the data and codes for our paper "[Bridging the Language Gaps in Large Language Models with Inference-Time Cross-Lingual Intervention](https://arxiv.org/pdf/2410.12462)".

### 1. Data 

Please download the data of downstream tasks and put it in ./data/

### 2. Intervention

For Discriminative and Generative tasks:

```
python intervention.py
```

For MGSM task:

```
python intervention_llama.py
```


### Citation
If you find this work is useful or use the data in your work, please consider cite our paper:

```
@inproceedings{DBLP:conf/acl/WangWHB25,
  author       = {Weixuan Wang and
                  Minghao Wu and
                  Barry Haddow and
                  Alexandra Birch},
  editor       = {Wanxiang Che and
                  Joyce Nabende and
                  Ekaterina Shutova and
                  Mohammad Taher Pilehvar},
  title        = {Bridging the Language Gaps in Large Language Models with Inference-Time
                  Cross-Lingual Intervention},
  booktitle    = {Proceedings of the 63rd Annual Meeting of the Association for Computational
                  Linguistics (Volume 1: Long Papers), {ACL} 2025, Vienna, Austria,
                  July 27 - August 1, 2025},
  pages        = {5418--5433},
  publisher    = {Association for Computational Linguistics},
  year         = {2025},
  url          = {https://aclanthology.org/2025.acl-long.270/},
  timestamp    = {Thu, 24 Jul 2025 21:25:39 +0200},
  biburl       = {https://dblp.org/rec/conf/acl/WangWHB25.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
