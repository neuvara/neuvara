Neuvara
Physics-informed AI for neurological disease diagnosis from brain MRI
Neuvara is building a next-generation brain MRI analysis platform designed to help clinicians identify rare and difficult-to-diagnose neurological diseases.

Current medical AI systems often struggle to generalise across hospitals because MRI scans vary significantly between scanner manufacturers, field strengths, acquisition protocols, and imaging centres. Neuvara's core focus is solving this challenge through physics-informed machine learning.

Our vision is a world where every brain MRI can be analysed consistently, regardless of where it was acquired, enabling earlier diagnosis, improved clinical decision-making, and better patient outcomes.

The Problem
Patients with rare neurological diseases often spend years searching for a correct diagnosis.

Many conditions are encountered so infrequently that even experienced specialists may only see a handful of cases during their careers. At the same time, MRI data is highly heterogeneous, making it difficult to build AI systems that generalise beyond the institutions where they were trained.

The result is delayed diagnosis, inconsistent interpretation, and missed opportunities for treatment.

Our Approach
1. Physics-Informed MRI Harmonisation
Before disease detection, MRI scans are normalised using acquisition-aware methods grounded in MRI physics.

By accounting for scanner hardware, field strength, pulse sequences, and imaging protocols, we aim to create representations that remain consistent across hospitals and imaging centres.

2. Shared Foundation Model for Brain MRI
A large self-supervised backbone learns general representations of brain structure from diverse MRI datasets.

Instead of training separate models from scratch for every disease, Neuvara uses a shared representation that captures anatomy, morphology, and pathological variation across populations.

3. Disease-Specific Intelligence
Lightweight disease-specific models build on top of the shared backbone, allowing effective learning even when only limited numbers of labelled cases are available.

4. Similarity-Based Clinical Reasoning
For unusual presentations or diseases not yet fully represented in training data, Neuvara can retrieve structurally similar confirmed cases from a reference database.

This provides clinicians with interpretable evidence rather than relying solely on probability scores.

Explainability
Clinical adoption requires transparency.

Neuvara integrates explainable AI techniques such as:

Grad-CAM
Integrated Gradients
Attention visualisation
Anatomical heatmap overlays
These tools help clinicians understand which regions of the brain influenced a prediction.

Long-Term Vision
Neuvara is being developed as a platform for physics-informed neuroimaging AI.

Future applications include:

Rare disease diagnosis
Epilepsy lesion detection
Neurodegenerative disease screening
Surgical planning support
Multi-centre clinical decision support systems
Status
Early-stage research and development.

Currently focused on:

MRI harmonisation research
Self-supervised representation learning
Multi-task disease classification
Similarity search systems
Clinical validation strategy
Mission
To build reliable, interpretable, and globally deployable AI systems for brain MRI analysis.
