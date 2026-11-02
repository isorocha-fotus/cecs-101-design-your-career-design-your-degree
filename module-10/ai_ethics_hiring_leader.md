
---

## Your Role

For this assignment, you are not a student writing a paper about AI ethics.

**You are the Chief People Officer (CPO) of Meridian Logistics** — a 4,200-person supply chain company headquartered in Nashville with distribution centers in six states. You report directly to the CEO. You own hiring, promotion, compensation, and workforce policy. When something goes wrong with how this company treats people, it lands on your desk.

Three weeks ago, your CEO forwarded you a vendor pitch with a one-line message:

> *"This could save us $2M a year. I want your recommendation by the end of the month. — R."*

This assignment is that recommendation.

You will investigate a real and unresolved problem — **the ethical dilemmas AI creates in hiring** — not as an observer, but as the person who has to decide, defend the decision, and live with the consequences.




---
### Meridian Logistics — Your Company Snapshot

| | |
|---|---|
| **Employees** | 4,200 |
| **Locations** | HQ in Nashville + 6 distribution centers (TN, GA, TX, OH, AZ, PA) |
| **Annual hires** | ~2,800 (high turnover in warehouse roles) |
| **Annual applications received** | ~140,000 |
| **Recruiting team** | 11 people |
| **Avg. time-to-hire** | 34 days |
| **Roles hired for** | Warehouse associates (70%), drivers (15%), dispatch/ops (10%), corporate/salaried (5%) |

Your recruiting team is drowning. Eleven people cannot meaningfully review 140,000 applications. Right now, they don't — they review whatever surfaces in the first two pages of the applicant tracking system and ignore the rest. Nobody calls that a screening system, but that is what it is.

---

### The Vendor: TalentSift AI

TalentSift is a well-funded HR technology company. Their product does four things:

**1. Résumé Ranking**
Scores and ranks every applicant 0–100 against the job description. Recruiters see only the top 5%.

**2. Video Interview Analysis**
Candidates record answers to preset questions. The system scores word choice, vocabulary complexity, speech pace, and facial expressiveness, producing "Communication," "Enthusiasm," and "Professionalism" scores.

**3. Attrition Risk Prediction**
Predicts the likelihood a candidate leaves within 12 months, based on patterns learned from your historical employee data.

**4. Automated Scheduling & Rejection**
Auto-advances top candidates and sends rejection emails to the rest.

---

### What TalentSift Claims

- Reduces time-to-hire by **61%**
- Reduces cost-per-hire by **$710**
- Projected annual savings for Meridian: **$2.1M**
- "Bias-mitigated models audited annually by an independent third party"
- "Increases diversity in candidate pools by removing human subjectivity"
- Used by 340+ enterprise clients

---

### What You Found When You Dug In

You asked harder questions than the sales deck anticipated. Here is what you learned:

1. **The attrition model was trained on Meridian's own last 8 years of employee data.** Your workforce during that period was 78% male in warehouse roles and 91% male in driver roles. Your turnover was highest among employees who lived more than 20 miles from a facility — and your facilities are located in areas where housing costs vary sharply by neighborhood.

2. **The "independent third party audit" was commissioned and paid for by TalentSift.** The full report is not available to clients. You were shown a two-page executive summary.

3. **TalentSift cannot explain individual scores.** When you asked why a specific sample candidate scored 34 instead of 71, their engineer said the model weighs "thousands of interacting features" and that per-candidate explanations are "not currently a supported feature."

4. **The video analysis tool has a documented accuracy gap.** Buried in the technical appendix: speech analysis accuracy is 6–11% lower for non-native English speakers and for candidates with speech disabilities. TalentSift characterizes this as "within industry-standard variance."

5. **Your General Counsel flagged legal exposure.** New York City, Illinois, Colorado, and the EU all have laws governing automated employment decisions. Meridian operates in none of those jurisdictions today — but is opening a facility in Illinois in 14 months.

6. **Your CEO has already told the board about the $2.1M.** It is in next year's projected budget.

7. **Two recruiters on your team have privately told you they are relieved.** They are exhausted. One said: *"Right now we reject 135,000 people by ignoring them. At least the machine would actually look at them."*

That last point is the one you cannot stop thinking about.

---



You do not have enough information. You will not get enough information. The deadline is real, the budget line is already in the board deck, and your recruiting team is burning out while you deliberate.

This is normal. Leadership is not the practice of deciding once you are certain. It is the practice of deciding well while uncertain, and then owning what follows.

Three standards for a defensible decision:

1. **It is specific.** "Proceed with caution" is not a decision. Name what happens Monday.
2. **It names its own costs.** A recommendation that claims no downside is a sales pitch.
3. **It can be wrong in a way you would notice.** State in advance what evidence would tell you the decision failed.

---

### Your Options

You are not limited to yes or no. Consider:

- **A — Full adoption** as proposed
- **B — Partial adoption:** license some modules, reject others
- **C — Conditional adoption:** proceed only if specific contractual requirements are met
- **D — Pilot:** limited deployment with human review and measurement before scaling
- **E — Reject TalentSift, solve the problem differently**
- **F — Reject and accept the status quo**
- **G — Something you design yourself**

If you choose B, C, D, or G, you must specify exactly what you are and are not adopting.

---


Write a **300-500 word** memo to the CEO. Executive register: direct, specific, no hedging, no filler. Lead with the recommendation.

## Part 6: Executive Decision Memo

**TO:** R. Castellanos, CEO
**FROM:** Ian Sorochan, Chief People Officer
**DATE:** November 2, 2026
**RE:** Recommendation — TalentSift AI Hiring Platform

---

### Recommendation
Do not sign the full TalentSift contract. Run a 90-day pilot of résumé ranking and automated scheduling only, for warehouse associate roles at two distribution centers, with a recruiter approving every rejection. We will not license video interview analysis or attrition prediction.

### Rationale
Our current process is not neutral. We reject roughly 135,000 applicants a year by never looking at them. A ranking tool that reads every application, with a person making the final call, is fairer than what we do today, and it gives our exhausted recruiters real relief.

The other two modules fail on TalentSift's own evidence. The attrition model learned from a 78–91% male workforce and penalizes long commutes, a proxy for neighborhood and income. It would turn past hiring patterns into future rules. Video analysis is 6–11% less accurate for non-native English speakers and people with speech disabilities. That is a discrimination claim waiting to happen.

We also cannot defend what we cannot explain. TalentSift cannot say why a candidate scored 34, and the only audit was paid for by TalentSift. If a rejected applicant or a regulator asks why, "the model decided" is not an answer.

Finally, we open in Illinois in 14 months, and Illinois already regulates AI video interviews and AI use in employment decisions. Building compliance in now is cheaper than retrofitting it.

### What This Costs Us
We will not hit $2.1M next year. Year-one savings will be well below the board projection, and I will bring you a revised number by day 90. Recruiters stay overloaded during the pilot, and reviewing every rejection adds work.

### Conditions and Requirements
1. TalentSift provides the full audit report, and we commission our own independent bias audit before any expansion.
2. Any candidate can request a plain-language explanation of their ranking.
3. No automated rejections. A recruiter approves every rejection.
4. Monthly selection-rate data by sex, race, age, and disability status, measured against the four-fifths rule.
5. We can exit at day 90 with no penalty.
6. TalentSift warrants compliance with Illinois law before any use there.

### Implementation
| Timeframe | Action | Owner |
|---|---|---|
| First 30 days | Negotiate terms; pick two pilot and two comparison sites; train recruiters | CPO, General Counsel |
| Days 31–90 | Run the pilot; review fairness and speed data monthly | Director of Recruiting |
| Days 91–180 | Expand, modify, or exit based on results; prepare Illinois compliance | CPO, General Counsel |

### How We Will Know If I Was Wrong
1. **Any group's selection rate falls below 80% of the highest group's.** We pause and investigate.
2. **Time-to-hire at pilot sites doesn't drop at least 25% versus comparison sites.** The savings case fails and we exit.
3. **Recruiters overturn more than 20% of the tool's rankings.** We stop at the pilot.

### What I Need From You
Approval to revise the $2.1M budget line with the board, and authority to walk away at day 90 if the data says so.

---

## Reflection

The hardest part of this assignment was the recruiter's comment that Meridian already rejects 135,000 people by ignoring them. My first instinct was to reject TalentSift completely, because the attrition model and video analysis clearly carried bias from the past. But rejecting it would have meant defending a process that isn't fair either, just less visible. That pushed me toward a middle option: use the part of the tool that helps everyone get looked at, and refuse the parts that judge people on things they can't control, like their accent or where they can afford to live.

What stood out most was how much depends on explainability and on who pays for the audit. A vendor can say "bias-mitigated" without anyone being able to check it. This connects directly to my own work. I build AI tools for clients, I'm taking AI 201 (AI, Ethics, and Legal Frameworks) this semester, and I want to build software for small food producers. If someone asks why my tool gave a certain answer, I need to be able to explain it. This assignment showed me that being the person who has to decide and defend a choice is very different from discussing ethics in the abstract, and that a good decision names its costs and how you'd know it failed.
