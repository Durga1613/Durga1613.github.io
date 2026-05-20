---
title: "Week 04 | Undergraduate Research Portfolio"
layout: default
---

<div style="background: linear-gradient(135deg, #1e3a8a, #3b82f6); padding: 35px 30px; border-radius: 12px; margin-bottom: 30px; color: white; box-shadow: 0 4px 10px rgba(37, 99, 235, 0.2);">
  <span style="background: rgba(255,255,255,0.2); padding: 4px 12px; border-radius: 20px; font-size: 0.8em; font-weight: bold; letter-spacing: 1px; text-transform: uppercase;">Phase 1: Literature & Data Acquisition</span>
  <h1 style="margin: 15px 0 5px 0; color: white; font-size: 2.5em;">Week 04 Update</h1>
  <p style="margin: 0; font-size: 1.1em; opacity: 0.9;">🗓️ May 18, 2026 - May 24, 2026</p>
</div>

<div style="background: white; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);">
  
  <h2 style="color: #1e3a8a; margin-top: 0; margin-bottom: 20px;">Identifying Dataset Constraints & Limitations</h2>

  <h3 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 0;"> Tasks & Accomplishments</h3>
  <p style="color: #334155;">This week concluded Phase 1 by performing a deep-dive audit of the Term-Preterm EHG Database (TPEHG) to map out the technical constraints our algorithms will need to overcome.</p>
  
  <ul style="color: #475569; line-height: 1.8;">
    <li><strong style="color: #2563eb;">Data Extraction Pipeline:</strong> Successfully set up a Google Colab environment and utilized the Python <code>wfdb</code> library to import and convert the raw <code>.dat</code> files into workable NumPy arrays.</li>
    <li><strong style="color: #2563eb;">Channel Configuration Mapping:</strong> Documented the dataset's specific electrode placement (3 bipolar channels) and confirmed the sampling frequency is downsampled to 20 Hz, which heavily influences our future filter design.</li>
    <li><strong style="color: #2563eb;">Statistical Auditing:</strong> Analyzed the clinical metadata to map the distribution of gestational ages at the time of recording versus actual delivery times.</li>
  </ul>

  <h3 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 30px;"> Challenges Faced</h3>
  <div style="background-color: #fef2f2; border-left: 4px solid #ef4444; padding: 15px; border-radius: 0 8px 8px 0;">
    <p style="margin: 0; color: #7f1d1d; line-height: 1.5;"><strong>Challenge (Class Imbalance):</strong> The dataset auditing revealed a significant class imbalance. There are far more 'Term' delivery records than 'Preterm' delivery records. If this raw data is fed directly into a machine learning model, the classifier will heavily bias toward predicting 'Term' simply because it is the statistical majority.</p>
  </div>

  <h3 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 30px;"> Next Steps (Week 05)</h3>
  <ul style="color: #475569; line-height: 1.8;">
    <li><strong>Officially begin Phase 2: Preprocessing & Analysis.</strong></li>
    <li>Structure the initial data preparation pipeline in Python to handle the newly imported NumPy arrays.</li>
    <li>Begin addressing major signal artifacts, specifically mapping out how to handle baseline wander and maternal respiration interference before applying digital filters.</li>
  </ul>

</div>

<div style="text-align: center; margin-top: 20px;">
  <a href="/" style="display: inline-block; background: #f1f5f9; color: #334155; padding: 10px 25px; border-radius: 8px; text-decoration: none; font-weight: bold; border: 1px solid #cbd5e1; transition: 0.2s;"> Back </a>
</div>
