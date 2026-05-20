---
title: "Week 02 | Undergraduate Research Portfolio"
layout: default
---

<div style="background: linear-gradient(135deg, #1e3a8a, #3b82f6); padding: 35px 30px; border-radius: 12px; margin-bottom: 30px; color: white; box-shadow: 0 4px 10px rgba(37, 99, 235, 0.2);">
  <span style="background: rgba(255,255,255,0.2); padding: 4px 12px; border-radius: 20px; font-size: 0.8em; font-weight: bold; letter-spacing: 1px; text-transform: uppercase;">Phase 1: Literature & Data Acquisition</span>
  <h1 style="margin: 15px 0 5px 0; color: white; font-size: 2.5em;">Week 02 Update</h1>
  <p style="margin: 0; font-size: 1.1em; opacity: 0.9;">🗓️ May 3, 2026 - May 10, 2026</p>
</div>

<div style="background: white; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);">
  
  <h2 style="color: #1e3a8a; margin-top: 0; margin-bottom: 20px;">Analyzing Existing Prediction Methods</h2>

  <h3 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 0;"> Tasks & Accomplishments</h3>
  <p style="color: #334155;">This week focused on evaluating the current state-of-the-art engineering approaches to preterm birth prediction. The goal was to understand which algorithms and signal features yield the highest clinical accuracy.</p>
  
  <ul style="color: #475569; line-height: 1.8;">
    <li><strong style="color: #2563eb;">Machine Learning Evaluation:</strong> Reviewed existing literature comparing traditional classifiers (Support Vector Machines, Random Forests) versus deep learning approaches for EHG signal classification.</li>
    <li><strong style="color: #2563eb;">Feature Extraction Review:</strong> Documented the most successful non-linear features used in recent papers, specifically noting the effectiveness of <em>Sample Entropy</em> and <em>Peak Frequency</em> in identifying early uterine contractions.</li>
    <li><strong style="color: #2563eb;">Identifying Research Gaps:</strong> Noted that many existing studies suffer from model overfitting due to small sample sizes or fail to properly remove maternal electrocardiogram (mECG) interference from the raw EHG recordings.</li>
  </ul>

  <h3 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 30px;"> Challenges Faced</h3>
  <div style="background-color: #fef2f2; border-left: 4px solid #ef4444; padding: 15px; border-radius: 0 8px 8px 0;">
    <p style="margin: 0; color: #7f1d1d; line-height: 1.5;"><strong>Challenge:</strong> There is a significant lack of standardization across existing research regarding which frequency bands yield the most predictive power. Some studies isolate the 0.34–0.8 Hz band, while others use 0.3–3.0 Hz, making it difficult to establish a definitive baseline for our upcoming DSP phase.</p>
  </div>

  <h3 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 30px;"> Next Steps (Week 03)</h3>
  <ul style="color: #475569; line-height: 1.8;">
    <li>Transition from literature review to practical data acquisition.</li>
    <li>Locate and download a verified, publicly available EHG clinical dataset to begin testing our own preprocessing theories.</li>
  </ul>

</div>

<div style="text-align: center; margin-top: 20px;">
  <a href="index.md" style="display: inline-block; background: #f1f5f9; color: #334155; padding: 10px 25px; border-radius: 8px; text-decoration: none; font-weight: bold; border: 1px solid #cbd5e1; transition: 0.2s;"> Back </a>
</div>
