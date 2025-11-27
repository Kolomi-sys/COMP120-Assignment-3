# 📰 Fake News Detector – SCRUM Project  
COMP120 – Assignment 3  
Version Control & Project Management

---

## Project Overview  
Fake News Detector is a simple tool that analyzes a news headline and identifies whether it is **Likely Real**, **Possibly Fake**, or **Likely Fake**.  
The system uses keyword detection, scoring logic, and color-coded output to help users quickly understand the credibility of a headline.

---

#  Sprint 1 – MVP  
**Duration:** Nov 20 – Nov 27  
**Goal:** Deliver a basic, functional Fake News Detector.

###  Sprint 1 Deliverables  
- Headline input box  
- Suspicious keyword detection  
- Fake-score (0–100)  
- Color-coded result (Green/Orange/Red)  
- Example button  
- Reset button  

---

# Product Backlog  

| ID | User Story Description |
|----|------------------------|
| SFP-1 | Enter a headline for analysis |
| SFP-2 | Keyword detection for suspicious words |
| SFP-3 | Fake-score between 0 and 100 |
| SFP-4 | Color-coded results |
| SFP-5 | Example button |
| SFP-6 | Reset button |
| SFP-7 | (Sprint 2) Train ML model |
| SFP-8 | (Sprint 2) Save analyzed headlines |

## ► Sprint 1 User Stories

---

<details>
<summary><strong>SFP-1 — As a Home User, I want to enter a headline so that I can analyze it</strong></summary>

###  Description  
The user enters a news headline into the system for instant analysis.

###  Acceptance Criteria  
- User can enter/paste a headline  
- On submit, the system performs analysis  
- Results show fake-score  
- Suspicious keywords are highlighted  
- User sees clear interpretation  
</details>

---

<details>
<summary><strong>SFP-2 — As a Home User, I want suspicious keyword detection so that I can understand risk</strong></summary>

###  Description  
The system scans for common misleading, emotional, or clickbait keywords.

###  Acceptance Criteria  
- System highlights suspicious keywords  
- Each keyword affects the score  
- User sees a list of detected keywords  
</details>

---

<details>
<summary><strong>SFP-3 — As a Home User, I want a fake-score (0–100) so that I can understand reliability</strong></summary>

###  Description  
The user receives a numeric reliability score based on the headline text.

###  Acceptance Criteria  
- Score is shown instantly after analysis  
- Higher = more likely real  
- Lower = more likely fake  
- Score displayed clearly  
</details>

---

<details>
<summary><strong>SFP-4 — As a Home User, I want color-coded results so I can understand output fast</strong></summary>

###  Acceptance Criteria  
- Green = Likely Real  
- Orange = Possibly Fake  
- Red = Likely Fake  
- Colors always match the score range  
</details>

---

<details>
<summary><strong>SFP-5 — As a Home User, I want an Example button so I can test quickly</strong></summary>

###  Acceptance Criteria  
- Example headline loads instantly  
- Auto-analysis happens on load  
- User does not type anything  
</details>

---

<details>
<summary><strong>SFP-6 — As a Home User, I want a Reset button so I can clear everything</strong></summary>

###  Acceptance Criteria  
- Clears input  
- Clears previous score  
- Clears highlighted keywords  
- User can start fresh  
</details>

---

#  Sprint 2 – Planned Work

<details>
<summary><strong>SFP-7 — Train a machine learning model</strong></summary>

###  Acceptance Criteria  
- Use dataset (CSV) for training  
- Build Logistic Regression or Naive Bayes  
- Model predicts fake/real based on text  
- Add confidence score  
</details>

---

<details>
<summary><strong>SFP-8 — Save previously analyzed headlines</strong></summary>

###  Acceptance Criteria  
- Store headline + result in a file/database  
- User can view previous analyses  
- History loads on startup  




