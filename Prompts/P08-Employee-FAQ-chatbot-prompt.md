# P08 · Employee FAQ assistant prompt

**Section:** 03 — Self-service support  
**Workflow step:** Step 8 of 10  
**Current version:** v1.2  
**Status:** ✅ Production-ready  
**Last updated:** March 2025  

---

## 📌 Prompt Text (v1.2 — current)

> Copy this exactly into your AI tool. Replace all `[PLACEHOLDERS]` before running.

You are a retail HR support assistant.

Answer a new employee’s onboarding question based only on approved onboarding information.

User question: [EMPLOYEE_QUESTION]

Rules:

Provide a clear and direct answer
If the answer depends on store-specific policy, state that clearly
If unsure, advise the employee to contact [MANAGER_NAME] or HR
Do not invent or assume policy details
Do not provide legal, payroll, or disciplinary advice

Format:

Start with a direct answer
Follow with one recommended next step if needed

Tone: helpful, calm, and professional
Length: maximum 120 words

---

## 🏢 Intended Workflow or Task

This prompt represents the **eighth step in the onboarding workflow**, supporting ongoing employee queries.

- **Trigger:** Employee has a question during onboarding or early employment  
- **Actor:** AI assistant (reviewed if necessary by HR)  
- **Purpose:** Provide quick, consistent answers to common onboarding questions  
- **Next step:** P09 — Exit interview summary (if employee leaves)  

**Workflow sequence:**
P07 Feedback → [P08 runs on demand] → Employee receives answer → HR escalation if needed

---

## ❗ Problem Being Solved

HR teams frequently receive repetitive onboarding questions such as:

- "What should I wear?"  
- "Who do I report to?"  
- "What if I am late?"  

This leads to:
- High volume of low-complexity queries  
- Delays in response time  
- Increased workload for HR staff  

---

## ⚡ Automation Potential

**Level: High**

| Dimension | Assessment |
|----------|-----------|
| Repetitiveness | Very high — common questions repeated frequently |
| Data availability | Based on standard onboarding information |
| Human judgment needed | Low for simple queries |
| Integration potential | Can be integrated into chatbot or HR portal |
| Estimated time saving | ~70% reduction in HR query handling time |

**Human-in-the-loop role:**  
Escalation to HR or manager for unclear or sensitive queries.

**Scalability:**  
Highly scalable across all stores and employees.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|------|-----------|
| Hallucination or incorrect answers | High | Restrict to approved information only |
| Overconfidence in responses | Medium | Include escalation rule for uncertainty |
| Handling sensitive queries incorrectly | High | Prohibit legal, payroll, disciplinary advice |
| Lack of context awareness | Medium | Encourage escalation when unclear |

**Overall risk rating:** MEDIUM–HIGH — requires strong constraints and escalation rules.

---

## 🔄 Version History

### v1.0 — Initial draft
**Prompt:**  
"Answer employee questions."

**Issues:**
- Too broad  
- Generated inaccurate or assumed answers  
- No boundaries or restrictions  

**Outcome:** High risk of incorrect information  

---

### v1.1 — Structured improvement
**Changes:**
- Added basic rules for answering  
- Improved clarity  

**Outcome:**
- More controlled responses  
- Still risk of overconfidence  

**Edit time:** ~10 minutes  

---

### v1.2 — Final version ✅
**Changes:**
- Added strict rules (no assumptions, escalation required)  
- Defined tone and structure  
- Restricted sensitive topics  

**Outcome:**
- Safe, controlled, and practical for onboarding support  
- Minimal supervision required for low-risk queries  

---

## 📊 A/B Testing Results

**Test group:** 3 HR coordinators (blind review)

| Criteria | v1.0 | v1.2 |
|----------|------|------|
| Accuracy control | 2/5 | 4.6/5 |
| Clarity | 2/5 | 4.7/5 |
| Safety | 1/5 | 4.8/5 |
| Practical usefulness | 2/5 | 4.7/5 |
| **Overall** | **1.75/5** | **4.7/5** |

---

## 🔗 Related Prompts

- **Previous:** P07 — 30-day feedback template  
- **Next:** P09 — Exit interview summary  
- **Workflow:** Employee support and onboarding system
