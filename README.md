# 📘 IL-ILGOV-2024: Indian Language Translation Benchmark

**IL-ILGOV-2024** is a multilingual **translation benchmark corpus** for Indian languages developed under the *HIndustani Machini ANuvaad TechnoloGY (HIMANGY)* / MTIL project, with **Hindi as source language** and **12 target languages** in the **governance domain**. ([ResearchGate][2])

This dataset is aimed at **evaluating and benchmarking machine translation (MT) systems** across Indian languages in a domain that reflects real-world governance text.

---

## 📦 Repository Contents

The repository contains:

```
nway_parallel.asm
nway_parallel.ban
nway_parallel.eng
nway_parallel.guj
nway_parallel.hin
nway_parallel.kan
nway_parallel.mal
nway_parallel.mar
nway_parallel.odi
nway_parallel.pan
nway_parallel.tam
nway_parallel.tel
nway_parallel.urd
```

Each file represents **N-way parallel sentence sets** for Indian language translation.

> ⚠️ *Note:* The repository currently lacks a descriptive README and metadata; this document serves to fill that gap.

---

## 📖 About the Dataset

### 🧠 Purpose

The **IL-ILGOV-2024 corpus** was created to provide a controlled benchmarking resource to assess the performance of MT systems translating **from Hindi to various Indian languages**. ([Springer][1])

### 🌐 Languages Covered

The corpus spans 12 languages:

| Code | Language  |
| ---- | --------- |
| hin  | Hindi     |
| ass  | Assamese  |
| ben  | Bangla    |
| eng  | English   |
| guj  | Gujarati  |
| kan  | Kannada   |
| mal  | Malayalam |
| mar  | Marathi   |
| odi  | Odia      |
| pan  | Punjabi   |
| tam  | Tamil     |
| tel  | Telugu    |
| urd  | Urdu      |

(*Note:* language codes reflect the file prefixes in this repository.)

### 📊 Data Structure

The benchmark corpus includes:

* **1304 n-way parallel sentences** across all languages.
* **Three bilingual splits**:

  * `dev`
  * `devtest`
  * `test`
    Each split contains between 1000 and 3000 sentence pairs for **Hindi ↔ target language** testing. ([ResearchGate][2])

### 🧾 Domain and Source

* Domain: **Governance** (policy, administrative text).
* Sentences were:

  * **Sourced online**
  * **Automatically aligned**
  * **Human-validated and corrected** for alignment and translation quality
    to ensure high reliability for benchmarking. ([ResearchGate][2])

---

## 🚀 Use Cases

This benchmark can be used for:

* **Evaluating MT models** across Indian language pairs.
* **Comparative performance analysis** (e.g., BLEU, COMET).
* **Training and testing multilingual MT systems** especially for low-resource Indian languages.
* **Domain-specific MT research** in governance.

---

## 📄 Published Paper

The dataset and methodology are described in the peer-reviewed article:

**Title:** *IL-ILGOV-2024: a translation benchmark for Hindi-to-12 languages in the governance domain*
**Authors:** Vandan Mujadia, Rao B. Ashwath, Dipti Misra Sharma
**Journal:** *Language Resources and Evaluation (2025)*
**Published:** 06 September 2025
**DOI:** [https://doi.org/10.1007/s10579-025-09859-8](https://doi.org/10.1007/s10579-025-09859-8) ([Springer][1])

This paper discusses:

* Purpose and motivation for the benchmark.
* Dataset creation pipeline including alignment and human validation.
* Benchmark statistics and structure.
* Utility for MT system evaluation.

---

## 📝 Citation

If you use this dataset or benchmark in your research, please cite the paper:

```
@article{Mujadia2025ILILGOV,
  title={IL-ILGOV-2024: a translation benchmark for Hindi-to-12 languages in the governance domain},
  author={Mujadia, Vandan and Ashwath, Rao B. and Misra Sharma, Dipti},
  journal={Language Resources and Evaluation},
  year={2025},
  pages={3851--3872},
  doi={10.1007/s10579-025-09859-8}
}
```

---

## 📬 Contact & Contributions

For questions or contributions, you may:

* Open an issue or pull request on the GitHub repository.
* Contact the dataset authors (see the paper for email addresses).

---

## 🧪 License

Please check the original repository or paper for licensing details. The current GitHub repo doesn’t specify a license yet.

---

If you want, I can also **generate sample evaluation scripts** (e.g., for BLEU/COMET scoring) or **annotate the data format** for easier integration with MT toolkits.

[1]: https://link.springer.com/article/10.1007/s10579-025-09859-8 "IL-ILGOV-2024: a translation benchmark for Hindi-to-12 languages in the governance domain | Language Resources and Evaluation | Springer Nature Link"
[2]: https://www.researchgate.net/publication/395334158_IL-ILGOV-2024_a_translation_benchmark_for_Hindi-to-12_languages_in_the_governance_domain?utm_source=chatgpt.com "IL-ILGOV-2024: a translation benchmark for Hindi-to-12 ..."
