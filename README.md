# Ivaylo Staykov

IT-Systems Engineering student at [HPI](https://hpi.de/en/).
Software Engineer Intern at [Taktile](https://taktile.com) - work account [@ivaylostaykov-work](https://github.com/ivaylostaykov-work).

---

### [proj-price-discovery](https://github.com/i-staykov/proj-price-discovery) · Price discovery after macro releases

How fast does the market incorporate new public information? The **fraction of the eventual move**
priced in after CPI and Employment Situation releases, estimated with a **Bayesian hierarchical
model** on BTCUSDT — crypto trades through the release, so no session boundary to model.
Preregistered analysis; tested calendar, ingestion and event-time alignment layers. A measurement
study, not a trading strategy.

`Python` · `Bayesian Inference`

### [proj-nonlinear-lda](https://github.com/i-staykov/proj-nonlinear-lda) · Nonlinear LDA in a normalizing flow

Train an invertible flow so that plain **linear** discriminant analysis, fit in the latent space `z = f(x)`,
becomes a **nonlinear** classifier in `x`. Affine coupling layers from scratch; flow and class-conditional
Gaussian base trained jointly by exact maximum likelihood. **0.855 → 0.962** test accuracy on two moons.

`PyTorch` · `Normalizing Flows`

### [proj-dl-ecg](https://github.com/i-staykov/proj-dl-ecg) · Interpretable ECG classification

Ventricular arrhythmia detection on MIT-BIH under cost-sensitive learning, where missing a beat costs more
than a false alarm. 1D-CNN against an MLP on an identical training loop: ventricular **F1 0.90 vs 0.62** at
0.98 recall. Saliency maps show the CNN attending to the QRS complex. Two-person course project.

`PyTorch` · `1D-CNN` · `Interpretability`

### [proj-internet-digital-ark](https://github.com/i-staykov/proj-internet-digital-ark) · Reproducible evidence pipeline

Historical domain names for 1996–2001, each backed by item-level, per-year evidence. Three verification
tiers, from a 10-second integrity check to a full rebuild from the original sources; the shipped results
rebuild **byte for byte** from the shipped evidence.

`Python` · `Data Engineering`

---

**Python** · **C++** · **SQL** · PyTorch · NumPy · scikit-learn · pandas · FastAPI · PostgreSQL · Docker · AWS · IaC · CI/CD · Git
