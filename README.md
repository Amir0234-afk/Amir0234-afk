<!-- PROFILE README: Amir0234-afk (v2 - stable, low-dependency) -->

![header](https://capsule-render.vercel.app/api?type=waving&height=210&section=header&text=Amir%20Ali%20Hosseini%20Abrishami&fontSize=46&fontAlignY=38&desc=Cybersecurity%20%7C%20Applied%20ML%20(NLP%2FCV)%20%7C%20Game%20Dev&descAlignY=60&color=gradient)

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=900&center=true&vCenter=true&width=720&lines=Cybersecurity+student+%7C+crypto-adjacent+tooling;Applied+ML%3A+Transformers+(NLP)+%E2%80%A2+U-Net+(CV);Game+prototyping%3A+Unreal+Engine+%E2%80%A2+Godot;Building+reproducible%2C+well-documented+projects"
    alt="Typing SVG"
  />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/amirali-hosseini-abrishami/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white">
  </a>
</p>

## Focus
- Applied ML (NLP/CV): clean experiments, reproducible training, readable results
- Security: small utilities + crypto-adjacent scripts
- Game dev: prototypes + tooling, packaged demos and short postmortems

## Pinned projects
- **sentiment-analysis-hf** — BERT/Transformers sentiment analysis (IMDB, SST-2): train/eval/batch predict
- **license-plate-segmentation-unet** — U-Net 3-class segmentation (TF/Keras)
- **CNN-Experiments-on-NIST-SD19-Handwritten-Characters** — modular CNN pipeline (NIST SD19): preprocess → train → evaluate
- **Base-FlappyBirdClone-UnrealEngine-5.1.1** — Unreal Engine Blueprint prototype base

## Stack 
- **Languages:** Python, C++, TypeScript, SQL, Bash
- **ML:** TensorFlow/Keras, Hugging Face Transformers
- **Infra / DevOps:** Docker, GitHub Actions (CI), PostgreSQL
- **Security/RE (tools I use):** WireShark, Ghidra
- **Game Development:** Unreal, Godot

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,ts,postgres,bash,linux,git,githubactions,docker,tensorflow&perline=11" />
</p>

## Samples (selected evidence)
> Selected qualitative and quantitative artifacts from pinned projects. Full analysis in individual repositories.

### Sentiment Analysis — Transformers (NLP)
<p align="center">
  <img src="assets/nlp-training-metrics.png" width="360" alt="Sentiment training metrics">
</p>

- **Accuracy:** 93.0% | **F1:** 0.93 | **Eval set:** 872 samples  
- Common failure modes: sarcasm/irony, stylistic negativity, mixed sentiment  
- Errors often show polarity inversion; low-confidence predictions correlate with ambiguity

---

### License Plate Segmentation — U-Net (CV)
<p align="center">
  <img src="assets/cv-unet-segmentation.png" width="360" alt="U-Net segmentation output">
</p>

- **Final metrics (50 epochs):**  
  Accuracy 0.9982 · Loss 0.0039 · Val Accuracy 0.9974 · Val Loss 0.0087  
- Qualitative mask overlays used for validation  
- License plates intentionally blurred for privacy

---

### Handwritten Character Classification — CNN
<p align="center">
  <img src="assets/cnn-confusion-matrix.png" width="360" alt="CNN confusion matrix">
</p>

- **Test Accuracy:** 0.7835  
- **F1:** Micro 0.7835 · Macro 0.7832 · Weighted 0.7832  
- Confusion matrix highlights class-level performance variance



![footer](https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=gradient)
