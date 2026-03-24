# 📊 SystemFit — Real-Time Team Fit Recommender  
*Players • Coaches • Staff — powered by current match data*

---
 
**Demo:** Streamlit MVP planned → simple cloud app if results look good

---

## 🧐 Why this exists

I’m a **Liverpool** fan, and I’ve watched **Manchester United** spend huge fees on big names without fixing their core problem: **fit**. The talent is there, but the pieces don’t always match the system.

SystemFit is my response: a small **ML-powered** tool that picks people who actually **fit a team’s current style**, starting with Manchester United as a case study and later extending to other clubs.

---

## 🎯 What it is

SystemFit is a personal project that helps a club choose the **right people for how they play now**.

It focuses first on **players**, with a roadmap to include **coaches and coaching staff**, using **live match data via APIs** — not static CSVs.

**Core Idea:** Rank by **fit + recent form**, not just reputation — and explain *why* picks make sense.

---

## 📌 MVP Scope

### 🔹 Input
- Team + role (e.g., pressing forward, ball-progressing CM)
- Constraints: budget, age, league

### 🔹 Output
- **Top-10 shortlist** with:
  - FitScore
  - Percentiles vs role peers
  - Simple recent-form trend
  - **Review zone** for borderline cases

### 🔹 Future Additions
- **Coach Fit:** match coach style cards to club profiles  
- **Staff Fit:** exploratory signals from role speciality + tenure  

---

## ⚙️ How it works (high level)

1. Pull **fresh stats** from public football APIs  
2. Compute **recent-form features** (last 6–10 games, adjusted for minutes + league strength)  
3. Compare candidates to the **team’s style + role needs**  
4. Rank players and generate **short, readable reasons**  
5. Send uncertain cases to a **review zone** for human judgment  

---

## 💡 Why it’s useful

- **Live** → updates after matches so shortlists don’t go stale  
- **Readable** → simple scores + plain-language explanations  
- **Practical** → moves clubs away from “big name” → toward **system fit**

---


---

