# P07 · 30-day feedback template generator

**Section:** 02 — Early performance support  
**Workflow step:** Step 7 of 10  
**Current version:** v1.2  
**Status:** ✅ Production-ready  
**Last updated:** March 2025  

---

## 📌 Prompt Text (v1.2 — current)

> Copy this exactly into your AI tool. Replace all `[PLACEHOLDERS]` before running.

You are an HR onboarding specialist for a retail company.

Create a 30-day performance feedback template for a [JOB_TITLE] working at [STORE_NAME].

Include:

Strengths demonstrated so far
Areas for improvement
Customer service performance
Teamwork and communication
Reliability and punctuality
Recommended support actions for the next 30 days

Format:

Use clear headings
Include short prompts under each section
Include a section for manager comments
Include a section for employee self-reflection

Tone: constructive, supportive, and professional
Length: maximum 250 words

Do NOT include:

Formal disciplinary language
Final employment decisions
Legal or contractual wording

---

## 🏢 Intended Workflow or Task

This prompt represents the **seventh step in the onboarding workflow**, focusing on early performance evaluation.

- **Trigger:** Employee completes initial work period (~30 days)  
- **Actor:** Store manager generates and reviews feedback template  
- **Purpose:** Provide structured, supportive performance feedback  
- **Next step:** P08 — Employee FAQ support  

**Workflow sequence:**
P06 Shift briefing → [P07 runs] → Manager completes feedback → Employee review → P08 support

---

## ❗ Problem Being Solved

Early-stage employee feedback in retail environments is often:

- Informal and inconsistent  
- Lacking structure or clarity  
- Focused only on issues rather than development  
- Not documented properly  

This can lead to:
- Miscommunication between staff and managers  
- Reduced employee engagement  
- Missed opportunities for early support  

---

## ⚡ Automation Potential

**Level: Medium–High**

| Dimension | Assessment |
|----------|-----------|
| Repetitiveness | Medium — structure is repeatable |
| Data availability | General performance categories available |
| Human judgment needed | High (manager input required) |
| Integration potential | Can be triggered at 30-day milestone |
| Estimated time saving | ~60% (20 min → ~8 min) |

**Human-in-the-loop role:**  
Manager completes and personalises feedback content.

**Scalability:**  
Useful across all stores to standardise early performance reviews.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|------|-----------|
| Overly generic feedback structure | Medium | Manager adds specific examples |
| Misinterpretation of feedback tone | Medium | Use supportive and neutral language |
| Use as formal performance evaluation | Medium | Clearly position as developmental feedback |
| Lack of context-specific detail | Low | Manager customisation required |

**Overall risk rating:** MEDIUM — requires human input for accuracy and fairness.

---

## 🔄 Version History

### v1.0 — Initial draft
**Prompt:**  
"Create a performance review template."

**Issues:**
- Too generic  
- No focus on early-stage employees  
- Lacked structured categories  

**Outcome:** Not suitable for onboarding use  

---

### v1.1 — Structured improvement
**Changes:**
- Added performance categories (e.g., teamwork, punctuality)  
- Improved clarity  

**Outcome:**
- More organised  
- Still lacked employee engagement elements  

**Edit time:** ~10 minutes  

---

### v1.2 — Final version ✅
**Changes:**
- Added employee self-reflection section  
- Included support-focused language  
- Added exclusions and word limit  

**Outcome:**
- Balanced, structured, and supportive  
- Minimal edits required (~3 minutes)  

---

## 📊 A/B Testing Results

**Test group:** 3 store managers (blind review)

| Criteria | v1.0 | v1.2 |
|----------|------|------|
| Clarity | 2/5 | 4.6/5 |
| Structure | 2/5 | 4.7/5 |
| Practical usefulness | 2/5 | 4.6/5 |
| Employee engagement | 2/5 | 4.5/5 |
| **Overall** | **2.0/5** | **4.6/5** |

---

## 🔗 Related Prompts

- **Previous:** P06 — Shift and roster briefing  
- **Next:** P08 — Employee FAQ assistant  
- **Workflow:** Onboarding and early performance support system
