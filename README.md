# Bachelor's thesis "Evaluating Language Diversity: Slot and Intent Detection for Bavarian and its Language Variation" for Compuational Linguistics @ LMU Munich

BaSID (Bavarian Slot and Intent Detection) and NaBaSID (Natural BaSID) are new slot and intent detection resources for Bavarian. 
We find that the task works well for English and German as well as Bavarian, a German dialect. We see that translated data can produce overly optimistic data even if the misclassifications show similar error patterns.

If you are interested in more details about the project, don't hesitate to reach out!

## ⭐ For the scientific release, please refer to "Slot and Intent Detection Resources for Bavarian and Lithuanian: Assessing Translations vs Natural Queries to Digital Assistants". 
[🟢 Link to the github repository](https://github.com/mainlp/xsid/tree/main)

## Corpus Statistics
### BaSID + BaVaSID (BaSID with dialect spelling variants)
![BaSID statistics](https://github.com/user-attachments/assets/23d4c6ae-4587-4b2f-ac9a-e9a402cc481a)
### NaBaSID (natural data collected from native speakers)
![NaBaSID statistics](https://github.com/user-attachments/assets/0b150c8f-0334-4dea-b854-c443c9fdd103)

## How to use this repository?
- `evaluation`: Evaluation code and results. 
- `machamp`: [MaChAmp (Van der Goot et al., 2021)](https://machamp-nlp.github.io/) repo with configs for the experiments.
- `train-data`: Manually translated data and natural data collected from native speakers.
- *sid.json* & *aux-mlm.json*: Training code.
