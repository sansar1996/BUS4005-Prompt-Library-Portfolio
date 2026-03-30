# P10 · Monthly HR onboarding insights report generator

**Section:** 05 — Management reporting  
**Workflow step:** Step 10 of 10  
**Current version:** v1.2  
**Status:** ✅ Production-ready  
**Last updated:** March 2025  

---

## 📌 Prompt Text (v1.2 — current)

> Copy this exactly into your AI tool. Replace all `[PLACEHOLDERS]` before running.

You are an HR reporting analyst for a retail company.

Create a monthly onboarding insights summary for management using the following inputs:

Number of new hires: [NEW_HIRES]
Number who completed induction on time: [ON_TIME]
Common onboarding issues: [ISSUES]
Early turnover cases: [TURNOVER]
Feedback themes: [FEEDBACK]

Include:

Key onboarding trends
Operational issues affecting new hires
Early turnover signals
Recommended actions for next month
A short executive summary

Format:

Use clear headings
Use bullet points where appropriate
Keep it suitable for management review

Tone: analytical, concise, and professional
Length: maximum 300 words

Do NOT include:

Personal employee identifiers
Unsupported assumptions or conclusions
Legal or compliance advice

---

## 🏢 Intended Workflow or Task

This prompt represents the **final step in the workflow**, focusing on management-level reporting.

- **Trigger:** Monthly onboarding data is collected  
- **Actor:** HR analyst reviews generated report  
- **Purpose:** Provide insights to management for decision-making  
- **Next step:** Continuous improvement of onboarding process  

**Workflow sequence:**
P09 Exit insights → [P10 runs] → HR review → Report shared with management → Process improvements

---

## ❗ Problem Being Solved

HR teams often spend time manually compiling onboarding data into reports, resulting in:

- Delays in reporting insights  
- Inconsistent analysis across months  
- Limited visibility into onboarding performance  
- Difficulty identifying trends or issues early  

This reduces the organisation’s ability to improve onboarding effectiveness.

---

## ⚡ Automation Potential

**Level: High**

| Dimension | Assessment |
|----------|-----------|
| Repetitiveness | High — recurring monthly reporting task |
| Data availability | Structured onboarding metrics available |
| Human judgment needed | Medium (validation and interpretation required) |
| Integration potential | Can be triggered monthly from HR systems |
| Estimated time saving | ~70% (30 min → ~10 min) |

**Human-in-the-loop role:**  
HR analyst validates insights and ensures accuracy before presenting to management.

**Scalability:**  
Highly scalable across multiple stores and regions.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|------|-----------|
| Misinterpretation of data trends | Medium | Require validated input data |
| Overgeneralisation of insights | Medium | Avoid unsupported conclusions |
| Data quality issues affecting output | High | Ensure data accuracy before use |
| Sensitive information exposure | Low | Exclude personal identifiers |

**Overall risk rating:** MEDIUM — dependent on data quality and human validation.

---

## 🔄 Version History

### v1.0 — Initial draft
**Prompt:**  
"Create a report about onboarding performance."

**Issues:**
- Too vague  
- No structured output  
- Lacked actionable insights  

**Outcome:** Not suitable for management use  

---

### v1.1 — Structured improvement
**Changes:**
- Added reporting categories (trends, issues)  
- Improved organisation  

**Outcome:**
- More useful  
- Still lacked clarity in recommendations  

**Edit time:** ~12 minutes  

---

### v1.2 — Final version ✅
**Changes:**
- Added executive summary  
- Included actionable recommendations  
- Added constraints and exclusions  

**Outcome:**
- Clear, concise, and management-ready  
- Minimal edits required (~3–5 minutes)  

---

## 📊 A/B Testing Results

**Test group:** 3 HR managers (blind review)

| Criteria | v1.0 | v1.2 |
|----------|------|------|
| Clarity | 2/5 | 4.7/5 |
| Insight quality | 2/5 | 4.8/5 |
| Usefulness for decisions | 2/5 | 4.7/5 |
| Structure | 2/5 | 4.8/5 |
| **Overall** | **2.0/5** | **4.8/5** |

---

## 🔗 Related Prompts

- **Previous:** P09 — Exit interview summary  
- **Workflow:** End-to-end onboarding and HR analytics system  
- **Outcome:** Continuous improvement of onboarding processes
