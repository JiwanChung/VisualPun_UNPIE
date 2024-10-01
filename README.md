# Can visual language models resolve textual ambiguity with visual cues? Let visual puns tell you!

This repository contains the code for our EMNLP 2024 paper:
***Can visual language models resolve textual ambiguity with visual cues? Let visual puns tell you!*** <br>
Jiwan Chung, Seungwon Lim, Jaehyun Jeon, Seungbeen Lee, Youngjae Yu <br>

## Data

Our recommendation is to access the corpus on HuggingFace:

```python

from datasets import load_dataset

# load main data
dset = load_dataset("jiwan-chung/VisualPun_UNPIE", "heterographic")

dset = load_dataset("jiwan-chung/VisualPun_UNPIE", "homographic")
```

## Evaluation

tbu
