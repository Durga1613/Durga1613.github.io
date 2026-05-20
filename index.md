---
title: "Preterm Birth Detection" 
       "using EHG signals and ML methods"
layout: default
---

<div style="background: linear-gradient(to right, #ffffff, #eff6ff); border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);">
  <table style="width: 100%; border: none; border-collapse: collapse;">
    <tr style="border: none;">
      <td style="border: none; padding: 0;">
        <h1 style="margin-top: 0; color: #3b82f6;">Sathasivam Durga</h1>
        <h4 style="margin-top: 10px; margin-bottom: 10px; color: #334155; font-weight: normal;">
          <strong>Electrical & Electronic Engineering</strong> | Signal Processing & Machine Learning
        </h4>
        <p style="margin-top: 0; margin-bottom: 15px; color: #64748b; font-size: 0.95em;">
          University of Peradeniya | Kandy, Sri Lanka
        </p>
        <p style="font-size: 0.95em;">
          <a href="https://www.linkedin.com/in/sathasivam-durga-821908315" style="text-decoration: none; background: #e0e7ff; color: #1d4ed8; padding: 4px 10px; border-radius: 6px; font-weight: bold; margin-right: 8px;">🔗 LinkedIn</a>
          <a href="mailto:e21120@eng.pdn.ac.lk" style="text-decoration: none; background: #e0e7ff; color: #1d4ed8; padding: 4px 10px; border-radius: 6px; font-weight: bold; margin-right: 8px;">✉️ Email </a>
          <a href="https://docs.google.com/document/d/15Rh5QakTWT68dJ6UjYreFPV0I2_ROaJRvMWKX8m49ho/edit?usp=sharing" style="text-decoration: none; background: #e0e7ff; color: #1d4ed8; padding: 4px 10px; border-radius: 6px; font-weight: bold;">📄 Resume</a>
        </p>
      </td>
      <td width="160" align="right" valign="top" style="border: none; padding: 0;">
        <img src="profile.jpg" alt="Sathasivam Durga Profile Picture" width="132" height="170" style="object-fit: cover; border: 3px solid #bfdbfe; border-radius: 8px; box-shadow: 0 4px 12px rgba(37, 99, 235, 0.15);">
      </td>
    </tr>
  </table>
</div>

<div style="background: white; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);">
  <h2 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 0;"> About Me</h2>
  <p style="color: #334155; line-height: 1.6;">I am a final-year engineering student specializing in digital signal processing (DSP) and machine learning. My academic focus and current research revolve around biomedical engineering—specifically, analyzing complex physiological data to build robust clinical prediction models. I am passionate about extracting meaningful features from noisy, real-world data and applying advanced algorithms to solve critical healthcare challenges.</p>
</div>

<div style="background: white; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);">
  <h2 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 0;">Technical Toolkit</h2>
  <ul style="color: #334155; line-height: 1.8; list-style-type: none; padding-left: 0;">
    <li><strong style="color: #2563eb;">Programming Languages:</strong> Python, MATLAB, C</li>
    <li><strong style="color: #2563eb;">Data Science & ML:</strong> scikit-learn, NumPy, SciPy, Predictive Modeling</li>
    <li><strong style="color: #2563eb;">Signal Processing:</strong> Digital Filtering, Fourier/Wavelet Transforms, Feature Extraction</li>
    <li><strong style="color: #2563eb;">Tools & Environments:</strong> Google Colab, Git, LaTeX, Overleaf</li>
  </ul>
</div>

<div style="background: white; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);">
  <h2 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 0;"> Project Overview: Preterm Birth Prediction</h2>
  
  <div style="background-color: #eff6ff; border-left: 4px solid #3b82f6; padding: 15px 20px; border-radius: 0 8px 8px 0; margin-bottom: 20px;">
    <h4 style="margin-top: 0; color: #1d4ed8;"> The Clinical Challenge</h4>
    <p style="margin-bottom: 0; color: #334155; line-height: 1.5;">Preterm birth remains a primary cause of neonatal mortality worldwide. Early detection of preterm labor risks is critical to providing timely clinical interventions. Traditional diagnostic methods often lack the sensitivity required to detect early uterine remodeling before active labor begins.</p>
  </div>

  <h4 style="color: #1e3a8a;">Our Approach</h4>
  <p style="color: #334155; line-height: 1.6;">This undergraduate research project focuses on developing a non-invasive, objective clinical prediction framework using advanced data analysis. By analyzing physiological parameters across multi-channel electrical recordings, the project leverages two primary modalities:</p>
  <ol style="color: #334155; line-height: 1.6;">
    <li><strong>Uterine Electromyography (EHG):</strong> Capturing the raw electrical activity of the uterine smooth muscle via abdominal electrodes.</li>
    <li><strong>Tocodynamometry (TOCO):</strong> Monitoring the mechanical pressure changes associated with uterine contractions.</li>
  </ol>

  <h4 style="color: #1e3a8a;">Methodology Pipeline</h4>
  <p style="color: #334155; line-height: 1.6;">The core of our research follows a rigorous four-stage engineering pipeline:</p>
  <ul style="color: #334155; line-height: 1.6;">
    <li><strong>Data Preparation & Preprocessing:</strong> Cleaning and structuring raw clinical datasets by removing motion artifacts, maternal heart rate interference, and baseline wander.</li>
    <li><strong>Digital Signal Processing (DSP):</strong> Applying bandpass filtering and executing time-frequency analysis to isolate contraction-specific signal trends.</li>
    <li><strong>Feature Extraction:</strong> Capturing essential statistical, frequency, and non-linear characteristics from the isolated signals.</li>
    <li><strong>Machine Learning Classification:</strong> Training and evaluating predictive algorithms (e.g., scikit-learn models) to classify signals into 'Term' or 'Preterm' categories and validating performance against benchmarks.</li>
  </ul>

  <div style="margin-top: 25px; padding-top: 15px; border-top: 1px dashed #cbd5e1;">
    <p style="margin: 0; color: #475569; font-size: 0.95em;"><strong>Supervisors:</strong> Prof. Roshan Godaliyadda, Prof. Parakrama Ekanayake, Dr. Ruwan Ranaweera, and Prof. Chathura Ratnayake.</p>
  </div>
  <div style="background: white; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);">
  <h2 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 0;"> Supervisors</h2>
  
  <div style="background: linear-gradient(to right, #eff6ff, #ffffff); border-left: 4px solid #2563eb; border-radius: 0 8px 8px 0; padding: 20px; margin-top: 15px;">
    <p style="margin-top: 0; margin-bottom: 12px; color: #334155; font-size: 1.05em;">
      <strong style="color: #1d4ed8;">Main Supervisor:</strong> Prof. Roshan Godaliyadda
    </p>
    <p style="margin-top: 0; margin-bottom: 8px; color: #334155;">
      <strong style="color: #1d4ed8;">Co-Supervisors:</strong>
    </p>
    <ul style="color: #475569; margin-top: 0; margin-bottom: 0; line-height: 1.6;">
      <li>Prof. Parakrama Ekanayake</li>
      <li>Dr. Ruwan Ranaweera</li>
      <li>Prof. Chathura Ratnayake</li>
    </ul>
    </div>
  </div>
</div>

<div style="background: white; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);">
  <h2 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 0;"> **14-Week Progress Timeline**</h2>
  <p style="color: #64748b; margin-bottom: 25px;">Welcome to my project documentation. This section tracks the progression of my final-year research based on our defined project milestones. Click on any week below to view detailed progress, code snippets, and research objectives.</p>

  <h4 style="color: #1d4ed8; margin-top: 30px; margin-bottom: 15px;">Phase 1: Literature & Data Acquisition</h4>
  <div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 20px;">
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #3b82f6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 01</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Initial Literature Review on EHG/TOCO Signals</p>
      <a href="week1.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #3b82f6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 02</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Analyzing Existing Preterm Birth Prediction Methods</p>
      <a href="week2.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #3b82f6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 03</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Exploring Publicly Available Datasets</p>
      <a href="week3.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #3b82f6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 04</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Identifying Dataset Constraints & Limitations</p>
      <a href="week4.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
  </div>

  <h4 style="color: #1d4ed8; margin-top: 30px; margin-bottom: 15px;">Phase 2: Preprocessing & Analysis</h4>
  <div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 20px;">
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #6366f1; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 05</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Structuring the Data Preparation Pipeline</p>
      <a href="week5.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #6366f1; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 06</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Developing Preprocessing Algorithms</p>
      <a href="week6.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #6366f1; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 07</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Implementing Signal Filtering Techniques</p>
      <a href="week7.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #6366f1; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 08</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Feature Extraction from EHG Signals</p>
      <a href="week8.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
  </div>

  <h4 style="color: #1d4ed8; margin-top: 30px; margin-bottom: 15px;">Phase 3: Machine Learning & Modeling</h4>
  <div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 20px;">
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #8b5cf6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 09</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Training Initial Machine Learning Models</p>
      <a href="week9.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #8b5cf6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 10</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Evaluating Model Performance</p>
      <a href="week10.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #8b5cf6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 11</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Pipeline Optimization & Hyperparameter Tuning</p>
      <a href="week11.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #8b5cf6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 12</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Advanced Validation & Testing</p>
      <a href="week12.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
  </div>

  <h4 style="color: #1d4ed8; margin-top: 30px; margin-bottom: 15px;">Phase 4: Finalization</h4>
  <div style="display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 20px;">
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #14b8a6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 13</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Experimental Comparisons with Existing Studies</p>
      <a href="week13.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
    <div style="background: #f8fafc; border: 1px solid #e2e8f0; border-top: 4px solid #14b8a6; border-radius: 8px; padding: 15px;">
      <h4 style="margin: 0 0 10px 0; color: #1e3a8a;">Week 14</h4>
      <p style="font-size: 0.85em; color: #64748b; margin-bottom: 15px;">Final Report Compilation & Future Improvements</p>
      <a href="week14.md" style="font-size: 0.85em; color: #2563eb; font-weight: bold; text-decoration: none;">View Details →</a>
    </div>
  </div>

</div>
