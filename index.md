---
title: " Undergraduate Research Portfolio"
layout: default
---

<table style="width: 100%; border: none; border-collapse: collapse;">
  <tr style="border: none;">
    <td style="border: none; padding: 0;">
      <h1 style="margin-top: 0; margin-bottom: 5px;">Undergraduate Research Portfolio</h1>
      <h2 style="margin-top: 0; color: #444;">Sathasivam Durga</h2>
      <h4 style="margin-top: 10px; margin-bottom: 5px; font-weight: normal;">
        <strong>Electrical & Electronic Engineering</strong> | Signal Processing & Machine Learning
      </h4>
      <p style="margin-top: 0; margin-bottom: 15px; color: #666;">
         University of Peradeniya | Kandy, Sri Lanka
      </p>
      <p style="font-size: 0.95em;">
        <a href="https://www.linkedin.com/in/sathasivam-durga-821908315" style="text-decoration: none;">🔗 LinkedIn</a> &nbsp; | &nbsp; 
        <a href="mailto:e21120@eng.pdn.ac.lk" style="text-decoration: none;">✉️ e21120@eng.pdn.ac.lk</a> &nbsp; | &nbsp; 
        <a href="https://docs.google.com/document/d/15Rh5QakTWT68dJ6UjYreFPV0I2_ROaJRvMWKX8m49ho/edit?usp=sharing" style="text-decoration: none;">📄 Resume</a>
      </p>
    </td>
    <td width="160" align="right" valign="top" style="border: none; padding: 0;">
      <img src="profile.jpg" alt="Sathasivam Durga Profile Picture" width="132" height="170" style="object-fit: cover; border: 1px solid #ddd; border-radius: 4px; padding: 4px; box-shadow: 0 4px 8px rgba(0,0,0,0.05);">
    </td>
  </tr>
</table>


##  About Me
I am a final-year engineering student specializing in digital signal processing (DSP) and machine learning. My academic focus and current research revolve around biomedical engineering—specifically, analyzing complex physiological data to build robust clinical prediction models. I am passionate about extracting meaningful features from noisy, real-world data and applying advanced algorithms to solve critical healthcare challenges.

---

## Technical Toolkit

* **Programming Languages:** Python, MATLAB, C
* **Data Science & ML:** scikit-learn, Pandas, NumPy, SciPy, Predictive Modeling
* **Signal Processing:** Digital Filtering, Fourier/Wavelet Transforms, Feature Extraction
* **Tools & Environments:** Google Colab, Git, LaTeX, Overleaf

---

##  Project Overview: Preterm Birth Prediction

### The Clinical Challenge
Preterm birth remains a primary cause of neonatal mortality worldwide. Early detection of preterm labor risks is critical to providing timely clinical interventions. Traditional diagnostic methods often lack the sensitivity required to detect early uterine remodeling before active labor begins.

### Our Approach
This undergraduate research project focuses on developing a non-invasive, objective clinical prediction framework using advanced data analysis. By analyzing physiological parameters across multi-channel electrical recordings, the project leverages two primary modalities:
1. **Uterine Electromyography (EHG):** Capturing the raw electrical activity of the uterine smooth muscle via abdominal electrodes.
2. **Tocodynamometry (TOCO):** Monitoring the mechanical pressure changes associated with uterine contractions.

### Methodology Pipeline
The core of our research follows a rigorous four-stage engineering pipeline:
* **Data Preparation & Preprocessing:** Cleaning and structuring raw clinical datasets by removing motion artifacts, maternal heart rate interference, and baseline wander.
* **Digital Signal Processing (DSP):** Applying bandpass filtering and executing time-frequency analysis to isolate contraction-specific signal trends.
* **Feature Extraction:** Capturing essential statistical, frequency, and non-linear characteristics from the isolated signals.
* **Machine Learning Classification:** Training and evaluating predictive algorithms (e.g., scikit-learn models) to classify signals into 'Term' or 'Preterm' categories and validating performance against benchmarks.

**Supervisors:** Prof. Roshan Godaliyadda, Prof. Parakrama Ekanayake, Dr. Ruwan Ranaweera, and Prof. Chathura Ratnayake.

---

##  Project Timeline & Weekly Progress

Welcome to my project documentation. This section tracks the progression of my final-year research based on our defined project milestones. Click on any week below to view detailed progress, code snippets, and research objectives.

* **Phase 1: Literature & Data Acquisition**
  * [Week 1: Initial Literature Review on EHG/TOCO Signals](week1.md)
  * [Week 2: Analyzing Existing Preterm Birth Prediction Methods](week2.md)
  * [Week 3: Exploring Publicly Available Datasets](week3.md)
  * [Week 4: Identifying Dataset Constraints & Limitations](week4.md)

* **Phase 2: Preprocessing & Analysis**
  * [Week 5: Structuring the Data Preparation Pipeline](week5.md)
  * [Week 6: Developing Preprocessing Algorithms](week6.md)
  * [Week 7: Implementing Signal Filtering Techniques](week7.md)
  * [Week 8: Feature Extraction from EHG Signals](week8.md)

* **Phase 3: Machine Learning & Modeling**
  * [Week 9: Training Initial Machine Learning Models](week9.md)
  * [Week 10: Evaluating Model Performance](week10.md)
  * [Week 11: Pipeline Optimization & Hyperparameter Tuning](week11.md)
  * [Week 12: Advanced Validation & Testing](week12.md)

* **Phase 4: Finalization**
  * [Week 13: Experimental Comparisons with Existing Studies](week13.md)
  * [Week 14: Final Report Compilation & Future Improvements](week14.md)
