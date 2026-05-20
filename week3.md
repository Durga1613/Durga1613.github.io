---
title: "Week 03 | Undergraduate Research Portfolio"
layout: default
---

<div style="background: linear-gradient(135deg, #1e3a8a, #3b82f6); padding: 35px 30px; border-radius: 12px; margin-bottom: 30px; color: white; box-shadow: 0 4px 10px rgba(37, 99, 235, 0.2);">
  <span style="background: rgba(255,255,255,0.2); padding: 4px 12px; border-radius: 20px; font-size: 0.8em; font-weight: bold; letter-spacing: 1px; text-transform: uppercase;">Phase 1: Literature & Data Acquisition</span>
  <h1 style="margin: 15px 0 5px 0; color: white; font-size: 2.5em;">Week 03 Update</h1>
  <p style="margin: 0; font-size: 1.1em; opacity: 0.9;">🗓️ May11, 2026 - May 17, 2026</p>
</div>

<div style="background: white; border: 1px solid #e2e8f0; border-radius: 12px; padding: 30px; margin-bottom: 30px; box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);">
  
  <h2 style="color: #1e3a8a; margin-top: 0; margin-bottom: 20px;">Exploring Publicly Available Datasets</h2>

  <h3 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 0;"> Tasks & Accomplishments</h3>
  <p style="color: #334155;">This week transitioned from theoretical literature review to hands-on data acquisition. The primary goal was to secure and understand the raw clinical data that will power our machine learning models.</p>
  
  <ul style="color: #475569; line-height: 1.8;">
    <li><strong style="color: #2563eb;">Dataset Acquisition:</strong> Successfully located and accessed the <strong>Term-Preterm EHG Database (TPEHG)</strong> via PhysioNet.</li>
    <li><strong style="color: #2563eb;">Structure Analysis:</strong> Mapped out the dataset directory, understanding the separation between physiological signal files (<code>.dat</code>) and the clinical header files (<code>.hea</code>).</li>
    <li><strong style="color: #2563eb;">Clinical Parameter Review:</strong> Documented the available maternal metadata included in the dataset, such as maternal age, parity, abortions, and gestational age at recording vs. delivery.</li>
  </ul>

  <h3 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 30px;"> Challenges Faced</h3>
  <div style="background-color: #fef2f2; border-left: 4px solid #ef4444; padding: 15px; border-radius: 0 8px 8px 0;">
    <p style="margin: 0; color: #7f1d1d; line-height: 1.5;"><strong>Challenge:</strong> Navigating the specific <em>WFDB (Waveform Database)</em> format used by PhysioNet. Standard Python libraries like Pandas cannot read these files natively, requiring research into specialized signal processing packages to extract the multi-channel EHG data into usable arrays.</p>
  </div>

  <h3 style="color: #1e3a8a; border-bottom: 2px solid #bfdbfe; padding-bottom: 10px; margin-top: 30px;"> Next Steps (Week 04)</h3>
  <ul style="color: #475569; line-height: 1.8;">
    <li>Identify and document any critical dataset constraints (e.g., class imbalances between Term and Preterm records).</li>
    <li>Set up the Python <code>wfdb</code> library in Google Colab to successfully import and plot a raw 30-minute EHG signal block.</li>
    <li>Conclude Phase 1 and prepare the workspace for Phase 2: Signal Preprocessing.</li>
  </ul>

</div>

<div style="text-align: center; margin-top: 20px;">
  <a href="index.md" style="display: inline-block; background: #f1f5f9; color: #334155; padding: 10px 25px; border-radius: 8px; text-decoration: none; font-weight: bold; border: 1px solid #cbd5e1; transition: 0.2s;"> Back </a>
</div>
