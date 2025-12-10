# Sedimentary Geochemistry — Interactive Learning Platform

[![GitHub Pages](https://img.shields.io/badge/Live-GitHub%20Pages-brightgreen)](https://caraxxhub.github.io/sedimentary-geochemistry/)
[![Course Level](https://img.shields.io/badge/Level-MSc-blue)](https://www.fau.de/)
[![Institution](https://img.shields.io/badge/FAU-GeoZentrum%20Nordbayern-teal)](https://www.gzn.nat.fau.de/)

An interactive web-based learning platform for Master's-level **Sedimentary Geochemistry** at Friedrich-Alexander-Universität Erlangen-Nürnberg (FAU).

---

## 🌍 Course Overview

This platform provides self-paced learning modules covering **isotope geochemistry** and **paleoenvironmental reconstruction** from sedimentary archives. Each module includes:

- Comprehensive concept explanations
- Interactive calculators
- Data interpretation exercises  
- Self-assessment quizzes

**Course Instructor:** PD Dr. Luca Caracciolo  
**Scientific Advisor:** Prof. Dr. Michael Joachimski  
**Institution:** GeoZentrum Nordbayern, FAU Erlangen-Nürnberg

---

## 📚 Available Modules

| Module | Topic | Duration | Status |
|--------|-------|----------|--------|
| 1 | **Introduction to Isotopes** — δ notation, fractionation, standards | 20-25 min | ✅ Live |
| 2 | **Carbon & Oxygen Isotopes** — Paleothermometry, ice volume, diagenesis | 30-35 min | ✅ Live |
| 3 | **Clumped Isotopes (Δ₄₇)** — Temperature-independent thermometry | 25-30 min | ✅ Live |
| 4 | **Boron Isotopes (δ¹¹B)** — Paleo-pH and pCO₂ reconstruction | 25-30 min | ✅ Live |
| 5 | **Strontium Isotopes (⁸⁷Sr/⁸⁶Sr)** — Weathering and stratigraphy | 25-30 min | ✅ Live |
| — | **Exam Simulation** — Comprehensive assessment | TBD | 🔒 Locked |

---

## 🔐 Access

This platform requires **FAU student credentials** to access.

**Login requirements:**
- Registered FAU email address
- Full name

**Student access expires:** February 5, 2026  
**Instructor access:** Unlimited

---

## 🛠️ Technical Details

- **Hosting:** GitHub Pages (static)
- **Authentication:** Client-side email verification
- **Session:** Persistent (localStorage)
- **Dependencies:** None (vanilla HTML/CSS/JS)
- **Browser Support:** Chrome, Firefox, Safari, Edge (modern versions)

---

## 📁 Repository Structure

```
sedimentary-geochemistry/
├── index.html                          # Landing page with login
├── module1_introduction_isotopes.html  # Module 1: Isotope fundamentals
├── module2_carbon_oxygen_isotopes.html # Module 2: C & O isotopes
├── module3_clumped_isotopes.html       # Module 3: Clumped isotopes (Δ₄₇)
├── module4_boron_isotopes.html         # Module 4: Boron isotopes (δ¹¹B)
├── module5_strontium_isotopes.html     # Module 5: Strontium isotopes
└── README.md                           # This file
```

---

## 🔧 For Administrators

### Adding New Students

Edit the `STUDENT_EMAILS` array in `index.html`:

```javascript
const STUDENT_EMAILS = [
    'existing@fauad.fau.de',
    'new.student@fauad.fau.de'  // Add new email
];
```

### Changing Expiration Date

Edit `EXPIRATION_DATE` in `index.html`:

```javascript
const EXPIRATION_DATE = new Date('2027-02-05T23:59:59');
```

### Adding New Modules

1. Create new HTML file: `module[N]_[topic].html`
2. Update `index.html` to link to new module
3. Change card from `coming-soon` class to active link

---

## 📖 Learning Objectives

By completing this course, students will be able to:

1. **Calculate** and **interpret** δ values using standard isotope notation
2. **Apply** paleothermometry equations (Anderson & Arthur, Kim & O'Neil)
3. **Distinguish** between primary signals and diagenetic overprinting
4. **Evaluate** ice volume effects on oxygen isotope records
5. **Interpret** carbon isotope excursions in terms of carbon cycle perturbations
6. **Design** multi-proxy approaches for paleoenvironmental reconstruction

---

## 📬 Contact

**Course inquiries:**  
PD Dr. Luca Caracciolo  
📧 [luca.caracciolo@fau.de](mailto:luca.caracciolo@fau.de)

**Scientific questions:**  
Prof. Dr. Michael Joachimski  
📧 [michael.joachimski@fau.de](mailto:michael.joachimski@fau.de)

---

## ⚖️ License

© 2025 GeoZentrum Nordbayern, FAU Erlangen-Nürnberg  
All rights reserved. Course materials are for enrolled students only.

---

*Last updated: December 2025*
