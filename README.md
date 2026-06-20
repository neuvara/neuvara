<div align="center">

# 🧠 Neuvara

**Physics-informed AI for neurological disease diagnosis from brain MRI**

*A world where every brain MRI can be analysed consistently — regardless of where it was acquired.*

![Alt text](https://github.com/neuvara/platform/raw/main/assets/images/banner.png)
![Alt text](https://github.com/neuvara/platform/raw/main/assets/images/banner.png)
![Alt text](https://github.com/neuvara/platform/raw/main/assets/images/banner.png)


</div>

---

## The Problem

Patients with rare neurological diseases often spend **years** searching for a correct diagnosis.

- Many conditions are so infrequently encountered that even experienced specialists may see only a handful of cases in their careers
- MRI data is highly heterogeneous — varying significantly across scanner manufacturers, field strengths, acquisition protocols, and imaging centres
- Existing medical AI systems struggle to generalise beyond the institutions where they were trained

**The result:** delayed diagnosis, inconsistent interpretation, and missed opportunities for treatment.

---

## Our Approach

### 1. 🔬 Physics-Informed MRI Harmonisation

Before disease detection, MRI scans are normalised using **acquisition-aware methods grounded in MRI physics**.

By accounting for scanner hardware, field strength, pulse sequences, and imaging protocols, we aim to create representations that remain consistent across hospitals and imaging centres — solving the generalisation problem at its root.

### 2. 🏗️ Shared Foundation Model for Brain MRI

A large self-supervised backbone learns general representations of brain structure from diverse MRI datasets.

Rather than training separate models from scratch for every disease, Neuvara uses a **shared representation** that captures anatomy, morphology, and pathological variation across populations.

### 3. 🎯 Disease-Specific Intelligence

Lightweight disease-specific models build on top of the shared backbone, enabling **effective learning even with limited labelled data** — critical for rare conditions where large annotated datasets simply don't exist.

### 4. 🔍 Similarity-Based Clinical Reasoning

For unusual presentations or diseases not yet fully represented in training data, Neuvara can retrieve structurally similar confirmed cases from a reference database.

This gives clinicians **interpretable evidence** rather than relying solely on probability scores.

---

## Explainability

Clinical adoption requires transparency. Neuvara integrates explainable AI techniques so clinicians can understand *which regions of the brain* influenced a prediction:

| Technique | Purpose |
|---|---|
| Grad-CAM | Gradient-weighted class activation maps |
| Integrated Gradients | Attribution along interpolation paths |
| Attention Visualisation | Transformer attention over image patches |
| Anatomical Heatmap Overlays | Predictions mapped onto standard brain atlases |

---

## Current Focus

> **Status:** Early-stage research and development

- [ ] MRI harmonisation research
- [ ] Self-supervised representation learning
- [ ] Multi-task disease classification
- [ ] Similarity search systems
- [ ] Clinical validation strategy

---

## Long-Term Vision

Neuvara is being built as a **platform for physics-informed neuroimaging AI**, with applications across:

- 🧬 Rare disease diagnosis
- ⚡ Epilepsy lesion detection
- 📉 Neurodegenerative disease screening
- 🔪 Surgical planning support
- 🏥 Multi-centre clinical decision support

---

## Mission

> *To build reliable, interpretable, and globally deployable AI systems for brain MRI analysis.*
