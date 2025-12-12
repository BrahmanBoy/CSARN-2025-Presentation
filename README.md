# CSARN-2025-Presentation
Slide deck for the CSARN 2025 presentation Assessing Public Transit Rider Awareness of Sex Trafficking of Minors. Includes methods, awareness insights, social media analytics, predictive modeling, and cross-city findings used to evaluate anti-trafficking transit campaigns.

# CSARN 2025 Conference Presentation  
### Assessing Public Transit Rider Awareness of Sex Trafficking of Minors  
**Authors:** John F. Betak (Collaborative Solutions LLC),  
**Ankit Sharma (Collaborative Solutions LLC)**,  
Christie L. Nelson (Rutgers DIMACS)

This repository contains the slide deck presented at the **3rd Annual Child Sexual Abuse Reduction Research Network (CSARN) Conference**, held at the University of Valencia, Spain (December 4–5, 2025).  
The presentation summarizes a multi-method research study evaluating public awareness of child sex trafficking across six U.S. transit agencies.

---

## Overview
The study integrates:
- **Awareness Assessment Survey** (Before/After comparisons) across 6 transit systems  
- **Social Media Data Mining & ML Classification** of 603K+ trafficking-related tweets  
- **Predictive Modeling** using spatial-temporal crime, business, and socioeconomic data  
- **Cross-City Analyses** for Chicago (CTA) and Portland (TriMet)  
- **Survivor-informed campaign design** via the PACT Survivors’ Council  

---

##  Key Research Components

### 1. Awareness Evaluation  
Surveyed riders in six U.S. cities to measure:
- Awareness of trafficking indicators  
- Perceived safety on transit  
- Knowledge of reporting procedures  
- Campaign recall (TV, stations, buses, digital)

### 2. Social Media Analytics  
Using 603,900 tweets, we:
- Built ML classifiers (**Random Forest achieved 0.966 accuracy**, :contentReference[oaicite:0]{index=0} page 11)  
- Identified escort-related hashtag patterns  
- Tracked spikes around major public events  
- Highlighted geographic distribution of suspicious activity (page 14)

### 3. Predictive Spatial-Temporal Modeling  
We modeled trafficking-related risk using:
- Crime records (5K+ trafficking-filtered cases in Chicago)  
- Transit infrastructure data  
- Hotel & business listings  
- Census and socioeconomic indicators  
- K-Means clustering and supervised ML (RF, SVM, XGBoost, Neural Network)

Key results:
- **Neural network achieved highest accuracy (68.5%) in Chicago** (page 20)  
- **Random Forest reached 74.7% accuracy for Portland** (page 23)  
- Event-driven spikes showed **up to 100× increases** in offenses (page 24)

---

##  Integrated Findings
- Survivor-informed campaign materials improve indicator recognition  
- Spatial-temporal ML identifies persistent hotspots near major transit corridors  
- Awareness gaps persist for vulnerable populations and reporting behavior  
- Multi-channel messaging (digital + station + vehicle ads) yields stronger retention  
- Predictive analytics offer a scalable framework for proactive safety interventions

---

##  Files in This Repository
- `CSARN_Presentation_2025.pdf` — Full slide deck presented at the conference  
- `README.md` — Overview, research summary, and findings  

---

##  Contact
For questions regarding the study:  
**John F. Betak** — john@collaborativesolutionsllc.com  
**Ankit Sharma** — ankit18293@gmail.com  

---

##  Citation
If referencing this work, please cite:

**Betak, J. F., Sharma, A., & Nelson, C. L.**  
*Assessing Public Transit Rider Awareness of Sex Trafficking of Minors*.  
Presented at CSARN 2025, University of Valencia, Spain.
