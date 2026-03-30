# P03 · Role briefing sheet generator

**Section:** 01 — Onboarding  
**Workflow step:** Step 3 of 10  
**Current version:** v1.2  
**Status:** ✅ Production-ready  
**Last updated:** March 2025  

---

## 📌 Prompt Text (v1.2 — current)

> Copy this exactly into your AI tool. Replace all `[PLACEHOLDERS]` before running.

You are an HR onboarding specialist for a retail company.

Draft a concise role briefing sheet for a new [JOB_TITLE] at [STORE_NAME].

Include:

Main purpose of the role
Key day-to-day responsibilities
Customer service expectations
Team collaboration expectations
Safety and compliance responsibilities
What success looks like in the first 30 days

Format:

Use clear headings
Use bullet points
Keep language simple for a new employee

Tone: supportive, practical, and professional
Length: maximum 250 words

Do NOT include:

Performance warnings
Confidential management information
Salary or contract clauses

---

## 🏢 Intended Workflow or Task

This prompt represents the **third step in the onboarding workflow**, following the induction schedule.

- **Trigger:** Induction schedule (P02) is finalised  
- **Actor:** HR coordinator generates and reviews the role briefing  
- **Purpose:** Provide a clear understanding of job expectations before Day 1  
- **Next step:** P04 — Training checklist is provided  

**Workflow sequence:**
P02 Induction schedule → [P03 runs] → HR review → Role briefing shared → P04 delivered

---

## ❗ Problem Being Solved

New employees often receive inconsistent or informal explanations of their role, leading to:

- Confusion about daily responsibilities  
- Misaligned expectations between staff and managers  
- Reduced confidence during the first few shifts  
- Increased early-stage errors  

Manual role briefings also vary in quality and completeness across different stores.

---

## ⚡ Automation Potential

**Level: High**

| Dimension | Assessment |
|----------|-----------|
| Repetitiveness | High — similar structure across roles |
| Data availability | Job title and store context available |
| Human judgment needed | Low–Medium (final review for accuracy) |
| Integration potential | Can be triggered automatically after P02 |
| Estimated time saving | ~65% (30 min → ~10–12 min) |

**Human-in-the-loop role:**  
Store manager reviews and adjusts details for role-specific nuances.

**Scalability:**  
Highly scalable across multiple locations and entry-level roles.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|------|-----------|
| Overly generic responsibilities | Medium | Manager customises final output |
| Missing role-specific details | Medium | Add store-level adjustments |
| Oversimplification of responsibilities | Low | Use structured sections to maintain completeness |
| Misinterpretation by new employees | Low | Keep language simple and reviewed |

**Overall risk rating:** LOW–MEDIUM — suitable with light human review.

---

## 🔄 Version History

### v1.0 — Initial draft
**Prompt:**  
"Explain the job role to a new employee."

**Issues:**
- Too vague  
- No structure  
- Output inconsistent and often too long  

**Outcome:** Required significant rewriting  

---

### v1.1 — Structured improvement
**Changes:**
- Added key sections (responsibilities, expectations)  
- Improved clarity  

**Outcome:**
- More organised output  
- Still lacked consistency and focus  

**Edit time:** ~12–15 minutes  

---

### v1.2 — Final version ✅
**Changes:**
- Added clear headings and bullet format  
- Introduced 30-day success criteria  
- Added exclusions and word limit  

**Outcome:**
- Clear, structured, and easy to understand  
- Minimal edits required (~3 minutes)  

---

## 📊 A/B Testing Results

**Test group:** 3 HR coordinators (blind review)

| Criteria | v1.0 | v1.2 |
|----------|------|------|
| Clarity | 2/5 | 4.7/5 |
| Structure | 2/5 | 4.8/5 |
| Practical usefulness | 2/5 | 4.6/5 |
| Completeness | 2/5 | 4.7/5 |
| **Overall** | **2.0/5** | **4.7/5** |

---

## 🔗 Related Prompts

- **Previous:** P02 — Induction schedule  
- **Next:** P04 — Training checklist  
- **Workflow:** Onboarding automation system
