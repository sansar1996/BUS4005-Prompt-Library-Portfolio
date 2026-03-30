# P04 · Training checklist generator

**Section:** 01 — Onboarding  
**Workflow step:** Step 4 of 10  
**Current version:** v1.2  
**Status:** ✅ Production-ready  
**Last updated:** March 2025  

---

## 📌 Prompt Text (v1.2 — current)

> Copy this exactly into your AI tool. Replace all `[PLACEHOLDERS]` before running.

You are an HR onboarding specialist for a retail company.

Create a new-hire training checklist for a [JOB_TITLE] at [STORE_NAME].

Include checklist items under these headings:

HR onboarding
POS and systems training
Customer service training
Health and safety
Store operations
End-of-week sign-off

Format:

Use a checklist format with checkboxes
Include who signs off each section (e.g., HR, supervisor)
Keep items specific and practical

Tone: operational and clear
Length: maximum 280 words

Do NOT include:

Legal wording
Sensitive internal procedures not suitable for new hires
Salary or contract information

---

## 🏢 Intended Workflow or Task

This prompt represents the **fourth step in the onboarding workflow**, following the role briefing.

- **Trigger:** Role briefing (P03) is completed  
- **Actor:** HR coordinator generates and reviews checklist  
- **Purpose:** Ensure all onboarding and training tasks are tracked and signed off  
- **Next step:** P05 — Store policy summary is shared  

**Workflow sequence:**
P03 Role briefing → [P04 runs] → HR review → Checklist used in training → P05 delivered

---

## ❗ Problem Being Solved

Training progress for new hires is often tracked manually or informally, leading to:

- Missed or incomplete training steps  
- Lack of accountability for task completion  
- Inconsistent onboarding quality across stores  
- Difficulty verifying compliance with required training  

Managers may rely on memory or informal notes, increasing the risk of gaps.

---

## ⚡ Automation Potential

**Level: Very High**

| Dimension | Assessment |
|----------|-----------|
| Repetitiveness | Very high — same checklist structure across roles |
| Data availability | Role and store details available |
| Human judgment needed | Low (review and minor edits only) |
| Integration potential | Can be triggered automatically after P03 |
| Estimated time saving | ~75% (30 min → ~7–10 min) |

**Human-in-the-loop role:**  
Supervisor confirms completion and signs off each section.

**Scalability:**  
Highly scalable across multiple stores, improving onboarding consistency and compliance tracking.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|------|-----------|
| Missing store-specific systems or tools | Medium | Supervisor adds local details |
| Checklist too generic | Medium | Include role-specific examples |
| Overlooking critical tasks | Low | Structured categories ensure coverage |
| Misuse as a compliance document | Low | Clarify it is a support tool, not legal documentation |

**Overall risk rating:** LOW–MEDIUM — requires minor local customisation.

---

## 🔄 Version History

### v1.0 — Initial draft
**Prompt:**  
"Create a training checklist for a new employee."

**Issues:**
- No structure or categories  
- Items too vague  
- No accountability or sign-off  

**Outcome:** Not practical for real use  

---

### v1.1 — Structured improvement
**Changes:**
- Added training categories  
- Introduced clearer checklist items  

**Outcome:**
- Improved organisation  
- Still lacked accountability and formatting clarity  

**Edit time:** ~12 minutes  

---

### v1.2 — Final version ✅
**Changes:**
- Added checkbox format  
- Included sign-off responsibility  
- Added exclusions and word limit  

**Outcome:**
- Clear, structured, and usable in real onboarding  
- Minimal edits required (~2–3 minutes)  

---

## 📊 A/B Testing Results

**Test group:** 3 HR coordinators (blind review)

| Criteria | v1.0 | v1.2 |
|----------|------|------|
| Clarity | 2/5 | 4.7/5 |
| Structure | 2/5 | 4.9/5 |
| Practical usability | 2/5 | 4.8/5 |
| Completeness | 2/5 | 4.7/5 |
| **Overall** | **2.0/5** | **4.8/5** |

---

## 🔗 Related Prompts

- **Previous:** P03 — Role briefing  
- **Next:** P05 — Store policy summary  
- **Workflow:** Onboarding automation system
