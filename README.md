````md
# 🧠 ParkinGuide

### Longitudinal Functional Intelligence for Parkinson’s Disease

**ParkinGuide** is an original **digital health product** designed for **longitudinal functional intelligence**, contextual monitoring, and personalized functional risk modelling in Parkinson’s disease.

Unlike traditional healthcare systems centered on isolated clinical snapshots, ParkinGuide focuses on what happens **between consultations**, transforming real-life behavioral, motor, emotional, and cognitive signals into structured longitudinal insights.

It is **not a diagnostic system**.

Its purpose is to support more informed, personalized, and context-aware neurological follow-up through explainable data interpretation and functional risk analysis.

---

## 🌍 Why this matters

Parkinson’s progression is deeply heterogeneous.

Two patients with the same diagnosis may evolve in completely different ways.

The same intervention may:

- improve one patient
- worsen another
- have no measurable effect on another

That means:

> **population averages are often insufficient for functional follow-up.**

ParkinGuide follows a **precision longitudinal health** approach:

```text
Each patient is interpreted against:
their own baseline
their own historical trajectory
their own functional context
````

Not against averages.

This enables truly personalized longitudinal care.

---

# 📸 Product Walkthrough

## 🏠 Home

Main product vision and positioning.

Longitudinal intelligence over episodic care.

![Home](docs/screenshots/home.png)

---

## 📊 Global Dashboard

Population-level contextual monitoring.

Includes:

* functional trends
* contextual signals
* cognitive activity
* wearable-ready variables
* recent clinical activity

![Dashboard](docs/screenshots/dashboard.png)

---

## 📈 Individual Longitudinal Monitoring — Moderate Risk

Personalized 24-week functional evolution.

Shows baseline-relative progression and contextual changes over time.

![Moderate Risk Profile](docs/screenshots/patient2.png)

---

## 🚨 Individual Longitudinal Monitoring — Critical Risk

Higher-risk progression profile showing accumulated contextual deterioration.

![Critical Risk Profile](docs/screenshots/patient4.png)

---

## 🎮 Cognitive-Motor Assessment Layer

Integrated mini-games for repeated functional observation.

Used to track cognitive speed, motor precision and executive activation.

![Games Module](docs/screenshots/juegos.png)

---

## 🗣️ Verbal Fluency Exercise

Example of a cognitive-motor task used to monitor executive function and language activation longitudinally.

![Verbal Fluency](docs/screenshots/fluidez_verbal.png)

---

## 📄 Weekly Clinical Report

Structured longitudinal PDF reports designed to improve neurologist-patient consultations.

![Clinical Report](docs/screenshots/informe.png)

---

# 🎯 Core Product Goal

ParkinGuide is built to:

* record real-world contextual variables
* detect functional deviations over time
* identify deterioration patterns
* improve continuity between consultations
* generate structured clinical summaries
* support explainable AI in personalized neurological care

---

# 🧩 Core Conceptual Framework

ParkinGuide is built around three complementary intelligence layers.

---

## 1️⃣ Baseline-Relative Modelling

The system compares:

```text
Current patient state
vs
their own historical baseline
```

Never against other patients.

Example:

```text
5,000 steps/day
```

may represent:

* normal stability for one patient
* significant decline for another

This enables:

> **personalized functional interpretation**

---

## 2️⃣ Multi-Source Contextual Observation

ParkinGuide supports:

* patient self-report
* caregiver observation
* combined reporting

This allows comparison between:

```text
perceived function
vs
observed function
```

These discrepancies may become clinically meaningful contextual signals.

---

## 3️⃣ Population-Trained Functional Intelligence

Synthetic longitudinal dataset:

```text
100 patients
24 weeks each
2400 weekly records
6000 cognitive-motor results
```

Used to model:

* nonlinear deterioration patterns
* variable interactions
* contextual instability
* habit-response dynamics

This layer enriches patient-level baseline modelling.

---

# 🩺 Neurology Continuity Layer

Designed to improve continuity between consultations.

Tracks:

* last neurology visit
* next scheduled visit
* neurologist reference
* review frequency

This creates:

> structured longitudinal continuity instead of fragmented episodic care

---

# 📊 Functional Variables Monitored

## Sleep

* sleep hours
* sleep quality
* awakenings
* sleep efficiency

## Physical Activity

* daily steps
* training hours
* active minutes
* falls

## Motor Symptoms

* tremor
* rigidity
* bradykinesia
* freezing
* balance confidence

## Emotional State

* mood
* stress
* motivation
* mental fatigue

## Social Context

* interactions
* isolation
* caregiver perception

## Nutrition

* hydration
* appetite
* constipation
* protein timing

## Wearable-Ready Variables

Prepared for future synchronization with:

* Apple Watch
* Garmin
* Fitbit
* Samsung Watch

Future integrations:

* HRV
* resting heart rate
* gait speed
* active minutes
* sleep efficiency

---

# 🎮 Cognitive-Motor Layer

Integrated assessments:

* Visual Memory
* Reaction Time
* Manual Coordination
* Verbal Fluency
* Number Sequence

Used to monitor:

* executive function
* cognitive speed
* motor precision
* memory evolution
* repeated functional patterns

---

# 🧠 Artificial Intelligence Architecture

ParkinGuide integrates two complementary AI systems.

---

## Explainable Contextual Intelligence

Rule-based layer.

Examples:

```text
low sleep + high fatigue
high freezing + low balance confidence
high stress + low activity
```

Produces:

```text
ContextInsight
```

Properties:

* transparent
* explainable
* auditable
* non-diagnostic

---

## Machine Learning Functional Risk Model

Current model:

```text
Random Forest Regressor
```

Predicts:

```text
functional_risk_score (0–100)
```

Why Random Forest:

* nonlinear modeling
* robust with mixed variables
* stable for medium datasets
* interpretable feature importance
* handles interaction effects well

---

# 📈 Current Model Performance

```text
MAE  = 3.59
RMSE = 4.84
R²   = 0.946
```

Top predictors:

1. Balance confidence
2. Sleep hours
3. Freezing episodes
4. Bradykinesia
5. Sleep quality
6. Daily steps
7. Social isolation
8. Mental fatigue

This means the model is already learning:

> **what tends to drive functional deterioration**

---

# 📄 Clinical Workflow

```text
Patient
   ↓
Weekly records
   ↓
Contextual AI
   ↓
Functional risk prediction
   ↓
Longitudinal visualization
   ↓
Clinical PDF report
   ↓
Neurology consultation
```

Outputs:

* contextual summary
* symptom evolution
* functional risk score
* cognitive history
* consultation-ready reports

---

# 🏗️ System Architecture

```text
Patient
   ↓
WeeklyRecord
   ↓
Longitudinal Database
   ↓
Context Engine
   ↓
Random Forest Predictor
   ↓
ContextInsight
   ↓
Longitudinal Visualization
   ↓
Clinical Report
```

---

# 🔐 Privacy by Design

Built with:

* pseudonymized IDs
* no real health identifiers
* explainable AI layers
* transparent logic
* responsible non-diagnostic positioning

Core principles:

* safety
* explainability
* responsibility
* clinical usefulness

---

# ⚙️ Tech Stack

## Backend

* Python
* Django

## Database

* SQLite
* PostgreSQL-ready architecture

## Frontend

* HTML
* CSS
* JavaScript
* Bootstrap

## Visualization

* Chart.js

## AI / Machine Learning

* Pandas
* NumPy
* Scikit-learn

## Reporting

* ReportLab

---

# 🚀 Current MVP Status

## Product

* [x] Longitudinal patient profiles
* [x] Weekly contextual records
* [x] Cognitive-motor tracking
* [x] Functional dashboard
* [x] Neurology continuity layer
* [x] Clinical PDF reports

## AI

* [x] Synthetic dataset generation
* [x] Functional risk engineering
* [x] Random Forest model
* [x] Real-time prediction
* [x] Context insight generation
* [x] Longitudinal risk visualization

## Next Roadmap

* [ ] Alert engine
* [ ] Wearable synchronization
* [ ] Per-patient explainability
* [ ] AI-generated consultation summaries
* [ ] Habit-response correlation engine

---

# 💡 Value Proposition

ParkinGuide does not try to predict Parkinson’s disease.

Its value is more clinically meaningful:

* understand how a patient is evolving
* identify what may be influencing deterioration
* detect which variables matter most
* improve the quality of clinical conversations

That makes it:

> **a functional intelligence layer for longitudinal neurological care**

---

# 👩‍💻 Author

**Bea Lamiquiz**

Backend Developer · Applied AI Product Developer · Digital Health Systems

GitHub:
https://github.com/beatriangu

LinkedIn:
https://www.linkedin.com/in/beatrizlamiquiz

---

# 📌 Final Project

Developed within:

**Laborlan — Artificial Intelligence and Technological Projects**

Focus areas:

* Applied AI
* Product thinking
* Explainable systems
* Precision health
* Longitudinal analytics

---

# 📜 Intellectual Property

ParkinGuide is an original proprietary digital health framework currently under active development.

Its conceptual architecture, longitudinal modelling methodology, contextual intelligence system and functional risk logic are original work by the author.

© 2026 Beatriz Lamiquiz. All rights reserved.

```
```
