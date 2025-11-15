---
title: "IndicDialogue: A dataset of subtitles in 10 Indic languages for Indic language modeling"
collection: publications
category: manuscripts
permalink: /publication/2024-08-01-indicdialogue-dataset
excerpt: 'Created a multilingual dataset of subtitles in 10 Indic languages for language modeling, demonstrating utility through text generation, word similarity, and word analogy tasks.'
date: 2024-08-01
venue: 'Data in Brief'
paperurl: 'https://doi.org/10.1016/j.dib.2024.110690'
---

This work introduces IndicDialogue, a comprehensive multilingual dataset containing subtitles from 10 low-resource Indic languages, addressing the scarcity of conversational data for these languages.
<img width="956" height="461" alt="image" src="https://github.com/user-attachments/assets/3abf00fb-6392-4494-b5c8-e4ffb705ac8f" />

**Key Contributions:**
- Corresponded with opensubtitles.org to obtain data across 10 Indic languages
- Curated and preprocessed subtitle data for language modeling tasks
- Fine-tuned a GPT-2 model on the dataset, demonstrating significant improvement in generated outputs
- Validated dataset utility through multiple downstream NLP tasks:
  - Text generation
  - Word similarity evaluation
  - Word analogy tasks
- Provided a valuable resource for the research community working on low-resource Indic languages

The dataset fills a critical gap in resources for Indic language NLP and enables research in dialogue systems, language modeling, and transfer learning for these underrepresented languages.

Read the paper [here](https://www.sciencedirect.com/science/article/pii/S2352340924006577)
[Implementation on GitHub](https://github.com/Codernob/IndicDialogue)

**Recommended citation:**

```bibtex
@article{arnob2024indicdialogue,
  title={IndicDialogue: A dataset of subtitles in 10 Indic languages for Indic language modeling},
  author={Arnob, Noor Mairukh Khan and Faiyaz, A and Fuad, Md Mubtasim and Al Masud, Shah Murtaza Rashid and Das, Baivab and Mridha, MF},
  journal={Data in Brief},
  volume={55},
  pages={110690},
  year={2024},
  publisher={Elsevier}
}
```
