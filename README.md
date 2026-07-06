# ComicVQA: A Benchmark for Visual Reasoning in Multimodal LLMs

---

Check out our paper [here](https://aclanthology.org/2026.findings-acl.1268/)

Check out our dataset [here](https://huggingface.co/datasets/project-works/ComicVQA)

**ComicVQA** is a specialized diagnostic benchmark designed to assess the visual reasoning capabilities of Multimodal Large Language Models (MLLMs) in the comics domain. ComicVQA focuses of 2 distinct reasoning tasks: 
1. **Missing Panel Prediction**: Predict the missing panel given a comic sequence.
2. **Panel Sorting**: Choose which of the 4 comic sequences is the correct arrangement.

These tasks leverage the sequential nature of comics to expose vulnerabilities in how models synthesize visual and textual information over a temporal sequence.

--github respository building in progress--

---

## 📂 Getting Started

### Dataset Viewing/Download 

The dataset is available on Hugging Face. You can browse the question images directly [here](https://huggingface.co/datasets/project-works/ComicVQA).

---

## 🖋️ Citation

Cite us!

```bibtex
@inproceedings{gan-etal-2026-comicvqa,
    title = "{C}omic{VQA}: A Benchmark for Visual Reasoning in Multimodal {LLM}s",
    author = "Gan, Esther  and
      Brown, Hannah  and
      Herel, David  and
      Kawaguchi, Kenji  and
      Kan, Min-Yen  and
      Shieh, Michael Qizhe",
    editor = "Liakata, Maria  and
      Moreira, Viviane P.  and
      Zhang, Jiajun  and
      Jurgens, David",
    booktitle = "Findings of the {A}ssociation for {C}omputational {L}inguistics: {ACL} 2026",
    month = jul,
    year = "2026",
    address = "San Diego, California, United States",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.findings-acl.1268/",
    pages = "25347--25370",
    ISBN = "979-8-89176-395-1",
    abstract = "We introduce Comic Visual Question Answering (\textbf{ComicVQA}), a comics-based benchmark for evaluating MLLMs on visual reasoning. ComicVQA comprises of (i) \textbf{Missing Panel Prediction}, testing fine-grained visual grounding and (ii) \textbf{Panel Sorting}, which evaluates sequential narrative understanding. Proprietary models achieve up to 62.6{\%} on Missing Panel Prediction and 46.4{\%} on Panel Sorting, whereas open-source models reach only 47.7{\%} and 26.9{\%}, respectively. In contrast, human annotators achieve over 83{\%} accuracy on both tasks, revealing a large gap between current models and human-level multimodal understanding in comics. Through controlled ordering ablations and a detailed error taxonomy, we show that current MLLMs rely primarily on coarse temporal cues and struggle with fine-grained visual reasoning. These findings demonstrate ComicVQA as a diagnostic benchmark for advancing multimodal visual reasoning in comics."
}
```
