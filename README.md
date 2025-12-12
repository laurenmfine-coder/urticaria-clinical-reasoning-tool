# 🩺 Chronic Urticaria Clinical Reasoning Tool

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-December%202025-blue.svg)]()
[![Evidence Base](https://img.shields.io/badge/Studies-158%20studies-green.svg)]()
[![Participants](https://img.shields.io/badge/Participants-~16%2C000-orange.svg)]()

> **An evidence-based learning tool integrating four AAAAI/ACAAI systematic reviews for mastering chronic urticaria management.**

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Quick Start](#-quick-start)
- [Features](#-features)
- [Evidence Base](#-evidence-base)
- [Repository Structure](#-repository-structure)
- [How to Use](#-how-to-use)
- [Learning Objectives](#-learning-objectives)
- [Target Audience](#-target-audience)
- [Citation](#-citation)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## 🎯 Overview

This comprehensive learning tool synthesizes the latest evidence from **four AAAAI/ACAAI Joint Task Force on Practice Parameters (JTFPP) systematic reviews** (2024-2025) into an interactive, multi-modal educational resource. It's designed to help clinicians and trainees develop clinical reasoning skills for evidence-based chronic urticaria management.

### What Makes This Tool Different

- **Evidence-first approach:** Every recommendation links to GRADE certainty ratings
- **Integrated content:** All four systematic reviews synthesized into cohesive learning modules
- **Multi-modal learning:** Cases, flashcards, quizzes, pearls, and gamified challenges
- **Clinical decision support:** NNT/NNH data for real-world counseling
- **Emerging therapies:** Coverage of remibrutinib, barzolvolimab, and pipeline agents

---

## 🚀 Quick Start

### Play the Interactive Game
1. Download `game/urticaria-challenge.html`
2. Open in any web browser
3. Choose Practice Mode (untimed) or Game Mode (scored)
4. Complete challenges to earn XP and unlock badges

### Browse the Clinical Compendium
1. Download `game/urticaria-compendium.html`
2. Open in any web browser
3. Navigate sections: Treatment Algorithm, Medications, Comparison Tables, Clinical Pearls

### Self-Study Path
1. Start with `evidence_summaries/JTFPP_systematic_reviews_integrated.md`
2. Review `tables/treatment_comparison_tables.md` for quick reference
3. Test yourself with `quizzes/quiz_bank_integrated.md`
4. Reinforce with `flashcards/flashcards_integrated.md`

---

## ✨ Features

### 🎮 Gamified Learning (`game/urticaria-challenge.html`)

| Feature | Description |
|---------|-------------|
| ⏱️ Timed Challenges | Race the clock for bonus points |
| 🔥 Streak Multipliers | Consecutive correct answers boost your score |
| 🏆 10 Achievement Badges | Unlock "Biologic Expert," "Evidence Guru," and more |
| 📈 7-Level Progression | Novice → Intern → Resident → Fellow → Attending → Expert → Master Clinician |
| ⭐ Star Ratings | Earn 1-3 stars per challenge based on accuracy |
| 🔓 Progressive Unlocks | Complete challenges to access harder content |
| 💾 Progress Saving | LocalStorage persistence between sessions |

**5 Challenge Categories:**
- Biologics Basics (Beginner)
- NNT/NNH Challenge (Intermediate)
- Treatment Algorithm (Intermediate)
- Failed Biologics (Advanced)
- Clinical Scenarios with Vignettes (Expert)

### 📚 Clinical Compendium (`game/urticaria-compendium.html`)

A comprehensive reference tool for clinicians featuring:

| Section | Content |
|---------|---------|
| 🔄 Treatment Algorithm | Visual step-by-step management approach |
| 💉 Biologics | Omalizumab, dupilumab, remibrutinib, barzolvolimab profiles |
| 💊 Immunomodulators | Cyclosporine, mycophenolate, sulfasalazine, dapsone |
| ➕ Adjunctive Therapies | LTRAs, systemic CS, topical CS with tabbed navigation |
| 📊 Comparison Tables | Efficacy, safety, NNT/NNH, decision factors |
| 💡 Clinical Pearls | High-yield facts for practice and boards |
| 📚 Evidence Summaries | Key findings from all 4 systematic reviews |

### 📚 Educational Content

| Component | Description | File |
|-----------|-------------|------|
| Evidence Summaries | Complete synthesis of all 4 systematic reviews | `evidence_summaries/` |
| Comparison Tables | 7 reference tables with efficacy, safety, NNT/NNH | `tables/` |
| Clinical Pearls | 47 high-yield pearls organized by topic | `pearls/` |
| Patient Cases | 10 tiered cases (Foundational → Advanced) | `cases/` |
| Quiz Bank | 23 questions with detailed explanations | `quizzes/` |
| Flashcards | 50 cards for spaced repetition | `flashcards/` |
| Treatment Algorithm | Visual stepwise approach with decision support | `algorithms/` |

---

## 📊 Evidence Base

This tool integrates four landmark systematic reviews totaling **~158 studies** and **~16,000 participants**:

| Review | Citation | Studies | Participants |
|--------|----------|---------|--------------|
| Systemic Corticosteroids | Chu X et al. JACI Practice 2024 | 12 RCTs | 944 |
| Leukotriene Receptor Antagonists | Rayner DG et al. JACI 2024 | 34 RCTs | 3,324 |
| Topical Corticosteroids | Chu AWL et al. Ann Allergy Asthma Immunol 2024 | 19 RCTs | 379 |
| Biologics/Immunomodulators NMA | Chu AWL et al. JACI 2025 | 93 studies | 11,398 |

### Key Treatment Rankings (Network Meta-Analysis)

**Most Effective for Urticaria Activity (HIGH Certainty):**
- Omalizumab 300mg Q4W: MD -8.37 on UAS7
- Remibrutinib: MD -7.65 on UAS7

**Critical Evidence Gaps:**
- Dupilumab: No angioedema outcome data
- High-dose omalizumab: No RCT comparisons
- Long-term safety: Limited data beyond 1 year

---

## 📁 Repository Structure

```
urticaria-clinical-reasoning-tool/
│
├── README.md                              # You are here
│
├── game/
│   ├── urticaria-challenge.html           # 🎮 Interactive gamified quiz
│   └── urticaria-compendium.html          # 📚 Clinical reference compendium
│
├── evidence_summaries/
│   └── JTFPP_systematic_reviews_integrated.md
│
├── tables/
│   └── treatment_comparison_tables.md     # 7 comparison tables
│
├── pearls/
│   └── clinical_pearls_integrated.md      # 47 clinical pearls
│
├── cases/
│   └── clinical_cases_integrated.md       # 10 tiered cases
│
├── quizzes/
│   └── quiz_bank_integrated.md            # 23 MCQs with explanations
│
├── flashcards/
│   └── flashcards_integrated.md           # 50 flashcards
│
└── algorithms/
    └── treatment_algorithm_2025.md        # Visual treatment algorithm
```

---

## 📖 How to Use

### For Individual Learners

1. **Start with the game** — `game/urticaria-challenge.html` provides an engaging entry point
2. **Deep dive into evidence** — Read the integrated systematic review summaries
3. **Quick reference** — Use comparison tables during clinical practice
4. **Self-assessment** — Complete quiz bank and track your progress
5. **Reinforce** — Use flashcards for spaced repetition

### For Educators

1. **Lecture preparation** — Clinical pearls and comparison tables are presentation-ready
2. **Small group discussions** — Use tiered cases for case-based learning
3. **Assessment** — Quiz bank questions can be adapted for examinations
4. **Flipped classroom** — Assign evidence summaries as pre-reading

### For Journal Clubs

1. Focus on one systematic review per session
2. Use the integrated summary as a discussion guide
3. Debate the clinical implications of evidence gaps

---

## 🎯 Learning Objectives

After completing this tool, learners will be able to:

1. **Interpret GRADE certainty ratings** and apply them to clinical decisions
2. **Explain the evidence hierarchy** for chronic urticaria treatments
3. **Select appropriate biologic therapy** based on patient characteristics and comorbidities
4. **Counsel patients** on benefits, harms, and evidence gaps using NNT/NNH
5. **Recognize treatment failures** and understand the pathophysiologic reasons
6. **Identify critical evidence gaps** that affect shared decision-making
7. **Apply the stepwise treatment algorithm** from antihistamines through biologics

---

## 👥 Target Audience

- Medical students and residents
- Allergy/Immunology fellows
- Dermatology trainees
- Practicing allergists and dermatologists
- Internal medicine and family medicine physicians
- Advanced practice providers (NPs, PAs)
- Pharmacists specializing in specialty medications

---

## 📝 Citation

If you use this tool in educational settings or publications, please cite:

```
Chronic Urticaria Clinical Reasoning Tool. (2025). 
Evidence-based learning resource integrating AAAAI/ACAAI JTFPP systematic reviews.
Available at: [repository URL]
```

### Primary Sources

Please also cite the original systematic reviews:

1. Chu X, et al. Efficacy and Safety of Systemic Corticosteroids for Urticaria. *J Allergy Clin Immunol Pract.* 2024;12(7):1879-1889.

2. Rayner DG, et al. Leukotriene receptor antagonists as add-on therapy to antihistamines for urticaria. *J Allergy Clin Immunol.* 2024;154(4):996-1007.

3. Chu AWL, et al. Topical corticosteroids for hives and itch (urticaria). *Ann Allergy Asthma Immunol.* 2024;133(4):437-444.

4. Chu AWL, et al. Comparative efficacy and safety of biologics and systemic immunomodulatory treatments for chronic urticaria. *J Allergy Clin Immunol.* 2025;156(4):1008-1023.

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Report Issues
- Found an error? Open an issue describing the problem
- Include the specific file and section

### Suggest Improvements
- Have ideas for new cases or questions? Submit a suggestion
- Want to add content for a specific audience? Let us know

### Submit Updates
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-content`)
3. Commit your changes (`git commit -m 'Add new clinical case'`)
4. Push to the branch (`git push origin feature/new-content`)
5. Open a Pull Request

### Content Guidelines
- All content must be evidence-based with citations
- Follow GRADE methodology for certainty assessments
- Maintain consistent formatting with existing materials

---

## ⚖️ License

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

**You are free to:**
- Share — copy and redistribute the material
- Adapt — remix, transform, and build upon the material

**Under the following terms:**
- Attribution — Give appropriate credit and link to the license
- NonCommercial — Not for commercial purposes without permission

---

## 🙏 Acknowledgments

### Evidence Sources
- AAAAI/ACAAI Joint Task Force on Practice Parameters
- Journal of Allergy and Clinical Immunology
- Annals of Allergy, Asthma & Immunology

### Methodology
- GRADE Working Group for certainty of evidence framework
- Cochrane Collaboration for systematic review standards

---

## 📬 Contact

For questions, suggestions, or collaboration inquiries, please open an issue on this repository.

---

## ⚠️ Disclaimer

This educational tool is designed to supplement, not replace, clinical judgment. Treatment decisions should be individualized based on patient preferences, comorbidities, local resources, and current guidelines. Evidence is current as of December 2025 and should be verified against the latest publications.

---

*Last updated: December 2025*
