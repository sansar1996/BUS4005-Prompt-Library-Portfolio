# P01 · New-hire welcome email

**Section:** 01 — Onboarding  
**Workflow step:** Step 1 of 10  
**Current version:** v1.2  
**Status:** ✅ Production-ready  
**Last updated:** March 2025  

---

## 📌 Prompt Text (v1.2 — current)

> Copy this exactly into your AI tool. Replace all `[PLACEHOLDERS]` before running.

You are an HR onboarding specialist for a retail company.

Draft a warm, professional welcome email for a new [JOB_TITLE] joining
[STORE_NAME] on [START_DATE].

Include the following sections:

Welcome and excitement about them joining
Brief overview of the role (2–3 sentences)
First-week schedule summary (refer to attached induction plan)
Key contacts: their line manager [MANAGER_NAME] and HR contact [HR_NAME]
One piece of motivational advice for their first week

Tone: warm, encouraging, and professional.
Length: maximum 220 words.
Do not include: salary details, contract terms, or personal data beyond name and role.

---

## 🏢 Intended Workflow or Task

This prompt represents the **first step in the onboarding communication workflow**.

- **Trigger:** New hire record is confirmed in HRIS  
- **Actor:** HR coordinator reviews and sends the output  
- **Purpose:** Deliver a consistent and personalised welcome message  
- **Next step:** P02 — Induction schedule is attached to the email  

**Workflow sequence:**
HRIS confirmation → [P01 runs] → HR review → Email sent → P02 attached

---

## ❗ Problem Being Solved

HR coordinators spend significant time manually drafting welcome emails for each new hire.

In a retail environment with high staff turnover, this creates:

- Inconsistent tone and quality across emails  
- Missing critical information (manager name, first-week expectations)  
- Delays in communication (often sent 2–3 days late)  

On average, this task takes **~45 minutes per employee**, making it inefficient at scale.

---

## ⚡ Automation Potential

**Level: High**

| Dimension | Assessment |
|----------|-----------|
| Repetitiveness | Very high |
| Data availability | All placeholders available in HRIS |
| Human judgment needed | Low (final review only) |
| Integration potential | Can be triggered from HRIS workflow |
| Estimated time saving | ~80% (45 min → ~8 min) |

**Human-in-the-loop role:**  
HR coordinator verifies placeholders and tone before sending.

**Scalability:**  
A store hiring 4 employees/month can save **~324 hours annually across multiple locations**.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|------|-----------|
| Missing or incorrect placeholders | Medium | Validate all HRIS fields before execution |
| Generic or impersonal tone | Low | HR review before sending |
| Accidental inclusion of confidential data | Low | Explicit prompt exclusions |
| Not suitable for senior roles | Low | Use separate prompt for management hires |

**Overall risk rating:** LOW — suitable for near-full automation with human oversight.

---

## 🔄 Version History

### v1.0 — Initial draft
**Prompt:**  
"Write a welcome email for a new staff member."

**Issues:**
- Too generic  
- Missing key details  
- Output too long (~380 words)  

**Outcome:** Required full rewrite  

---

### v1.1 — Structured prompt
**Changes:**
- Added role framing ("HR onboarding specialist")  
- Introduced section-based structure  

**Outcome:**
- Improved clarity  
- Still inconsistent length  

**Edit time:** ~14 minutes  

---

### v1.2 — Final version ✅
**Changes:**
- Added word limit (220 words)  
- Added exclusions (salary, contract details)  

**Outcome:**
- Consistent and professional output  
- Minimal edits required (~2 minutes)  

---

## 📊 A/B Testing Results

**Test group:** 3 HR coordinators (blind review)

| Criteria | v1.0 | v1.2 |
|----------|------|------|
| Readability | 2/5 | 4.7/5 |
| Completeness | 1/5 | 4.8/5 |
| Tone | 3/5 | 4.5/5 |
| Send-ready | 0/5 | 4/5 |
| **Overall** | **1.5/5** | **4.5/5** |

---

## 🔗 Related Prompts

- **Next:** P02 — Induction schedule  
- **Used with:** P03 — Role briefing  
- **Workflow:** Onboarding automation system

