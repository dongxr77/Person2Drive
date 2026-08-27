# Person2Drive

## Driving Like Yourself: A Benchmark for Closed-Loop Personalized End-to-End Autonomous Driving

**ECCV 2026**

[![arXiv](https://img.shields.io/badge/arXiv-2602.18757-b31b1b.svg)](https://arxiv.org/abs/2602.18757)
[![Dataset](https://img.shields.io/badge/🤗%20Hugging%20Face-Dataset-yellow)](https://huggingface.co/datasets/dongxr7/Person2Drive)
[![Conference](https://img.shields.io/badge/ECCV-2026-blue)](#)

---

## 🔥 News

* **[2026]** Person2Drive is accepted to **ECCV 2026**.
* **[2026/02]** The Person2Drive paper is available on arXiv.
* **[Coming soon]** Code, pretrained models, and evaluation tools will be released in this repository.

---

## 📖 Overview

Existing end-to-end autonomous driving systems typically learn a single standardized driving policy, while human drivers exhibit diverse and consistent driving preferences in aspects such as speed, acceleration, braking, and interaction with surrounding traffic.

**Person2Drive** introduces a benchmark for **closed-loop personalized end-to-end autonomous driving**. It studies whether an autonomous driving system can adapt its behavior to a specific driver based on personalized driving demonstrations and reproduce that driver's driving preferences.

The benchmark includes driving demonstrations from **50 drivers** and evaluates personalization from both **offline** and **closed-loop** perspectives. In addition to driving performance, Person2Drive evaluates whether learned personalized behaviors remain consistent when transferred to **unseen routes and scenarios**.

<!--
Optional: add the main benchmark/framework figure here after uploading it to assets/.

<p align="center">
  <img src="assets/overview.png" width="95%">
</p>
-->

---

## 📊 Benchmark

Person2Drive evaluates personalized end-to-end autonomous driving from several complementary perspectives:

* **Offline Evaluation:** measures trajectory quality and consistency with individual driving behavior.
* **Closed-Loop Evaluation:** evaluates personalized driving policies in interactive driving environments.
* **Personalization Evaluation:** measures how closely generated driving behavior matches the preferences of a target driver.
* **Generalization Evaluation:** examines whether personalized behavior learned from observed routes can transfer to unseen routes and scenarios.

Detailed evaluation protocols, metrics, and benchmark scripts will be released together with the code.

---

## 📦 Dataset

The Person2Drive dataset contains personalized driving demonstrations collected from **50 drivers** for studying personalized end-to-end autonomous driving.

The dataset is hosted on Hugging Face:

👉 **[Person2Drive Dataset on Hugging Face](https://huggingface.co/datasets/dongxr7/Person2Drive)**

Detailed information about dataset organization, data format, annotations, and downloading instructions can be found on the Hugging Face dataset page.

---

## 🚀 Getting Started

The codebase is currently being organized for public release.

Detailed documentation will be provided for:

* Installation
* Dataset preparation
* Training
* Offline evaluation
* Closed-loop evaluation
* Pretrained models

After the code release, this section will provide the main entry points for reproducing the Person2Drive benchmark and experiments.

---

## 🔐 Ethics & Privacy

Person2Drive is released for research purposes.

* Driver identities in the released dataset are anonymized.
* Personally identifiable information is not intended to be included in the public release.
* The dataset should be used in accordance with applicable research ethics requirements and dataset usage terms.

Additional details regarding data collection, privacy protection, and dataset usage will be provided with the public release.

---

## 🔗 Links & Status

* 📄 **Paper:** [arXiv:2602.18757](https://arxiv.org/abs/2602.18757)
* 🎓 **Conference:** ECCV 2026
* 💻 **Code:** This repository
* 📦 **Dataset:** [Person2Drive on Hugging Face](https://huggingface.co/datasets/dongxr7/Person2Drive)
* 🧠 **Pretrained Models:** Coming soon
* 🛠️ **Evaluation Tools:** Coming soon

---

## 🙏 Acknowledgements

Person2Drive builds upon several excellent open-source autonomous driving projects and benchmarks.

Detailed acknowledgements, third-party dependencies, and corresponding licenses will be provided together with the public code release.

---

## 📚 Citation

If you find Person2Drive useful in your research, please consider citing our work:

```bibtex
@article{dong2026person2drive,
  title={Driving Like Yourself: A Benchmark for Closed-Loop Personalized End-to-End Autonomous Driving},
  author={Dong, Xiaoru and others},
  journal={arXiv preprint arXiv:2602.18757},
  year={2026}
}
```

The citation will be updated with the official **ECCV 2026** publication information after the final proceedings are available.

---

## 📄 License

License information will be added together with the public code release.
