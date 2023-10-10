# Sentence-level Feedback Generation for English Language Learners: Does Data Augmentation Help?


This is our submission to GenChal:FCG@INLG2023:

> [Sentence-level Feedback Generation for English Language Learners: Does Data Augmentation Help?](https://aclanthology.org/2023.inlg-genchal.8) <br>
> [Shabnam Behzad](https://shabnam-b.github.io/), [Amir Zeldes](https://corpling.uis.georgetown.edu/amir/), [Nathan Schneider](https://people.cs.georgetown.edu/nschneid/) <br>

<br>
To create pseudo-data:
- Download ICNALE "Edited Essays" version from [here](https://language.sakura.ne.jp/icnale/download.html), it includes essay pairs: the original and the corrected version.
- You can find W&I+LOCNESS sentence pairs [here](https://www.cl.cam.ac.uk/research/nl/bea2019st/#data).
- You can run [ERRANT](https://github.com/chrisjbryant/errant) to get error types.
- You can fine-tune T5 by adapting [this script](https://github.com/philschmid/deep-learning-pytorch-huggingface/blob/main/training/flan-t5-samsum-summarization.ipynb).


## Citation
If you find this work useful for your research, please cite our paper:

```
@inproceedings{behzad-etal-2023-sentence,
    title = "Sentence-level Feedback Generation for {E}nglish Language Learners: Does Data Augmentation Help?",
    author = "Behzad, Shabnam  and
      Zeldes, Amir  and
      Schneider, Nathan",
    booktitle = "Proceedings of the 16th International Natural Language Generation Conference: Generation Challenges",
    month = sep,
    year = "2023",
    address = "Prague, Czechia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.inlg-genchal.8",
    pages = "53--59",}
```
