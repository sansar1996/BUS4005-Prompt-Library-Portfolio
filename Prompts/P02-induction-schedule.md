# P02 · Induction schedule generator

**Section:** 01 — Onboarding  
**Workflow step:** Step 2 of 10  
**Current version:** v1.2  
**Status:** ✅ Production-ready  
**Last updated:** March 2025  

---

## 📌 Prompt Text (v1.2 — current)

> Copy this exactly into your AI tool. Replace all `[PLACEHOLDERS]` before running.

You are an HR onboarding specialist for a retail company.

Create a structured first-week induction schedule for a new [JOB_TITLE] at [STORE_NAME].

Include:

Day-by-day breakdown (Day 1–Day 5)
Training activities (POS system, store policies, safety procedures)
Shadowing sessions with team members
Break times and onboarding meetings
End-of-week review checkpoint

Format:

Use a table
Include time slots
Keep it clear and practical

Tone: professional and structured
Length: maximum 300 words

Do NOT include:

Salary details
Internal confidential policies

---

## 🏢 Intended Workflow or Task

This prompt represents the **second step in the onboarding workflow**, following the welcome email.

- **Trigger:** Welcome email (P01) has been sent  
- **Actor:** HR coordinator reviews and finalises schedule  
- **Purpose:** Provide a clear and structured first-week plan  
- **Next step:** P03 — Role briefing is provided to the employee  

**Workflow sequence:**
P01 Welcome email → [P02 runs] → HR review → Schedule shared → P03 delivered

---

## ❗ Problem Being Solved

First-week induction schedules are often created manually by store managers or HR staff, leading to:

- Inconsistent onboarding experiences across stores  
- Missing essential training components (e.g., POS, safety)  
- Lack of structured time allocation  
- Confusion for new hires about expectations  

On average, creating a schedule takes **30–60 minutes per employee**, especially when done from scratch.

---

## ⚡ Automation Potential

**Level: Very High**

| Dimension | Assessment |
|----------|-----------|
| Repetitiveness | Very high |
| Data availability | Role and store information readily available |
| Human judgment needed | Low (final adjustment only) |
| Integration potential | Can be triggered automatically after P01 |
| Estimated time saving | ~70% (45 min → ~12–15 min) |

**Human-in-the-loop role:**  
Store manager or HR reviews schedule for local adjustments.

**Scalability:**  
Useful across all stores with high onboarding volume, ensuring consistent training quality.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|------|-----------|
| Overly generic schedule | Medium | Add role-specific examples and review locally |
| Missing store-specific tasks | Medium | Manager customises final output |
| Overloaded or unrealistic schedule | Low | Controlled via structure and word limit |
| Misalignment with store operations | Low | Final approval required before sharing |

**Overall risk rating:** LOW–MEDIUM — requires light human review before use.

---

## 🔄 Version History

### v1.0 — Initial draft
**Prompt:**  
"Create a first-week plan for a new employee."

**Issues:**
- No structure  
- Output was paragraph-based  
- Missing time allocation and training details  

**Outcome:** Not usable without full rewrite  

---

### v1.1 — Structured improvement
**Changes:**
- Added day-by-day breakdown  
- Introduced training categories  

**Outcome:**
- More organised output  
- Still inconsistent formatting  

**Edit time:** ~15 minutes  

---

### v1.2 — Final version ✅
**Changes:**
- Added table format requirement  
- Included time slots  
- Added exclusions and word limit  

**Outcome:**
- Clear, structured, and practical output  
- Minimal edits required (~3–5 minutes)  

---

## 📊 A/B Testing Results

**Test group:** 3 HR coordinators (blind review)

| Criteria | v1.0 | v1.2 |
|----------|------|------|
| Clarity | 2/5 | 4.6/5 |
| Structure | 1/5 | 4.8/5 |
| Practical usability | 2/5 | 4.5/5 |
| Completeness | 2/5 | 4.7/5 |
| **Overall** | **1.75/5** | **4.6/5** |

---

## 🔗 Related Prompts

- **Previous:** P01 — Welcome email  
- **Next:** P03 — Role briefing  
- **Workflow:** Onboarding automation system
