# P05 · Store policy summary generator

**Section:** 01 — Onboarding  
**Workflow step:** Step 5 of 10  
**Current version:** v1.2  
**Status:** ✅ Production-ready  
**Last updated:** March 2025  

---

## 📌 Prompt Text (v1.2 — current)

> Copy this exactly into your AI tool. Replace all `[PLACEHOLDERS]` before running.

You are an HR onboarding specialist for a retail company.

Summarise the key workplace policies a new [JOB_TITLE] needs to understand before starting at [STORE_NAME].

Include:

Attendance and punctuality expectations
Dress code and presentation standards
Breaks and roster expectations
Customer service behaviour standards
Workplace health and safety basics
Escalation process (who to contact for help)

Format:

Use short headings
Use plain, simple English
Keep content easy to read for a new employee
End with a reminder to read full official policy documents

Tone: friendly, professional, and compliance-aware
Length: maximum 260 words

Do NOT include:

Full policy documents
Legal interpretation or advice
Confidential disciplinary procedures
Salary or contract details

---

## 🏢 Intended Workflow or Task

This prompt represents the **fifth step in the onboarding workflow**, following the training checklist.

- **Trigger:** Training checklist (P04) is prepared  
- **Actor:** HR coordinator generates and reviews summary  
- **Purpose:** Provide a simplified overview of key policies before Day 1  
- **Next step:** P06 — Shift/roster briefing is sent  

**Workflow sequence:**
P04 Training checklist → [P05 runs] → HR review → Policy summary shared → P06 delivered

---

## ❗ Problem Being Solved

Retail employees are often given lengthy policy documents that are:

- Difficult to read and understand quickly  
- Overwhelming for new hires  
- Frequently ignored or only partially reviewed  

This increases the risk of:
- Policy misunderstandings  
- Compliance issues  
- Inconsistent behaviour across staff  

---

## ⚡ Automation Potential

**Level: Medium–High**

| Dimension | Assessment |
|----------|-----------|
| Repetitiveness | High — policies are standard across stores |
| Data availability | Policy content already exists |
| Human judgment needed | Medium (must ensure accuracy) |
| Integration potential | Can be triggered after P04 |
| Estimated time saving | ~60% (25 min → ~10 min) |

**Human-in-the-loop role:**  
HR reviews to ensure accuracy and alignment with official policies.

**Scalability:**  
Highly useful across all stores to ensure consistent policy communication.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|------|-----------|
| Oversimplification of policies | Medium | Include reminder to consult full documents |
| Missing important policy details | Medium | HR validation required |
| Misinterpretation by employees | Low | Use clear, simple language |
| Use as replacement for official policies | Medium | Explicit disclaimer in output |

**Overall risk rating:** MEDIUM — requires HR validation before use.

---

## 🔄 Version History

### v1.0 — Initial draft
**Prompt:**  
"Summarise company policies for new staff."

**Issues:**
- Too broad  
- Output too long and complex  
- Included unnecessary legal language  

**Outcome:** Not suitable for onboarding use  

---

### v1.1 — Structured improvement
**Changes:**
- Added key policy categories  
- Simplified language  

**Outcome:**
- More readable  
- Still inconsistent in tone and length  

**Edit time:** ~10–12 minutes  

---

### v1.2 — Final version ✅
**Changes:**
- Added plain-language requirement  
- Introduced exclusions (legal, confidential content)  
- Added word limit and structure  

**Outcome:**
- Clear, concise, and onboarding-friendly  
- Minimal edits required (~2–4 minutes)  

---

## 📊 A/B Testing Results

**Test group:** 3 HR coordinators (blind review)

| Criteria | v1.0 | v1.2 |
|----------|------|------|
| Clarity | 2/5 | 4.6/5 |
| Readability | 2/5 | 4.8/5 |
| Practical usefulness | 2/5 | 4.5/5 |
| Compliance alignment | 2/5 | 4.6/5 |
| **Overall** | **2.0/5** | **4.6/5** |

---

## 🔗 Related Prompts

- **Previous:** P04 — Training checklist  
- **Next:** P06 — Shift/roster briefing  
- **Workflow:** Onboarding automation system
