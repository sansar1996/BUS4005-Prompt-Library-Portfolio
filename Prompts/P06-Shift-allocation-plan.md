# P06 · Shift and roster briefing generator

**Section:** 02 — Early operations  
**Workflow step:** Step 6 of 10  
**Current version:** v1.2  
**Status:** ✅ Production-ready  
**Last updated:** March 2025  

---

## 📌 Prompt Text (v1.2 — current)

> Copy this exactly into your AI tool. Replace all `[PLACEHOLDERS]` before running.

You are an HR onboarding specialist supporting store operations.

Draft a first-roster briefing message for a new [JOB_TITLE] at [STORE_NAME].

Include:

Their first scheduled shifts (dates and times)
Who they report to on each shift
What they need to bring or prepare
Arrival expectations (e.g., arrive early, check in)
Who to contact if they are late, sick, or need help

Format:

Use short paragraphs
Use a simple bullet list for shift details
Keep it suitable for email or SMS format

Tone: clear, reassuring, and professional
Length: maximum 180 words

Do NOT include:

Pay rates or salary details
Unconfirmed or draft roster information
Personal contact details unless provided

---

## 🏢 Intended Workflow or Task

This prompt represents the **sixth step in the onboarding workflow**, transitioning from onboarding to operational readiness.

- **Trigger:** Policy summary (P05) is shared  
- **Actor:** HR coordinator or store manager reviews output  
- **Purpose:** Clearly communicate first working shifts and expectations  
- **Next step:** P07 — 30-day feedback template preparation  

**Workflow sequence:**
P05 Policy summary → [P06 runs] → Manager review → Shift briefing sent → P07 prepared

---

## ❗ Problem Being Solved

New employees often experience confusion about their first shifts due to:

- Lack of clear communication about schedule details  
- Uncertainty about who to report to  
- Missing practical instructions (arrival time, preparation)  
- Inconsistent messaging across stores  

This can result in:
- Late arrivals  
- Increased anxiety for new hires  
- Disruption to store operations  

---

## ⚡ Automation Potential

**Level: High**

| Dimension | Assessment |
|----------|-----------|
| Repetitiveness | High — similar message format for all new hires |
| Data availability | Roster details available in scheduling systems |
| Human judgment needed | Low (confirmation required only) |
| Integration potential | Can be triggered after roster finalisation |
| Estimated time saving | ~65% (20 min → ~7–8 min) |

**Human-in-the-loop role:**  
Store manager verifies accuracy of shift details before sending.

**Scalability:**  
Highly scalable across multiple stores with frequent shift onboarding.

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
|------|------|-----------|
| Incorrect shift details included | High | Only use confirmed roster data |
| Missing store-specific instructions | Medium | Manager customises final output |
| Miscommunication of expectations | Low | Use structured format and clear tone |
| Over-reliance on automated message | Low | Human review before sending |

**Overall risk rating:** LOW–MEDIUM — dependent on accurate input data.

---

## 🔄 Version History

### v1.0 — Initial draft
**Prompt:**  
"Write a message telling a new employee about their shifts."

**Issues:**
- Too informal  
- Missing key details (reporting manager, expectations)  
- No structure  

**Outcome:** Required full rewrite  

---

### v1.1 — Structured improvement
**Changes:**
- Added shift details and reporting information  
- Improved clarity  

**Outcome:**
- More useful output  
- Still inconsistent formatting  

**Edit time:** ~10 minutes  

---

### v1.2 — Final version ✅
**Changes:**
- Added structured format (bullets + short paragraphs)  
- Included exclusions (unconfirmed roster, salary)  
- Added tone and word limit  

**Outcome:**
- Clear, practical, and ready to send  
- Minimal edits required (~2–3 minutes)  

---

## 📊 A/B Testing Results

**Test group:** 3 HR coordinators (blind review)

| Criteria | v1.0 | v1.2 |
|----------|------|------|
| Clarity | 2/5 | 4.7/5 |
| Practical usability | 2/5 | 4.8/5 |
| Accuracy control | 2/5 | 4.6/5 |
| Structure | 2/5 | 4.7/5 |
| **Overall** | **2.0/5** | **4.7/5** |

---

## 🔗 Related Prompts

- **Previous:** P05 — Store policy summary  
- **Next:** P07 — 30-day feedback template  
- **Workflow:** Onboarding and early operations system
