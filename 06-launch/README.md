# Collection Date Self-Service for Responsible Payers

> Eligible payers can change their direct-debit collection date in the portal and see which installment will be affected, without contacting support.

**Lisa Preuschoff + Riverty PM** · https://github.com/preu052/pm-final-project

Prototype: https://chatgpt.com/c/6ac755de-c990-8336-ad0b-a684a74a2a39

---

## Final Project Deliverables

### Slide 5 · Strategy
- **Problem:** # Problem Hook & Value Proposition: [StreamLine / RouteLogic / your initiative]

> **Module 1 · ★ Deliverable 1.** Repo file `01-product-thinking/problem-hook.md` — part of your submission.
> Do the lab in the **Module 1 · Exercise 2 Guide** (linked from the Module 1 deck), then click **⬇ Download .md** — it saves as this exact file. Commit it here.
> It becomes the **Problem, Value & Hypothesis** slide of your Module 6 final deck. (Your Module 1 · Exercise 1 discovery map lands in `strategic-map.md`.)

## 1. Chosen scenario

**Path:** _StreamLine Spotlight (B2C) · RouteLogic Velocity (B2B) · my own initiative_

_One line on why you picked it._

## 2. The strategic crisis

_The big-picture business risk. If the company does nothing for 12 months, what happens to its market position?_

> If we do nothing for 12 months, the company will…

## 3. The moment of misery

_The specific point where the product fails the user, forcing a manual workaround (Google, spreadsheets, group texts, a competitor)._

> The user is currently forced to…

## 4. Problem hook

_One urgent sentence fusing the business risk and the user pain, your pitch for why this is the most important thing to work on right now._

> We must solve [business risk] by addressing [user pain]…

## 5. Value proposition

_Who it's for, the new value, and why it's urgent to launch now._

> For **[who]**, we will **[value]** because **[urgent why]**.

## 6. Cold-read self-review

_Read your hook back as a skeptical stakeholder. If you don't feel the urgency, that's your data._

| Question | Your answer |
|---|---|
| Is the business risk high-stakes enough to justify a new initiative? | _____ |
| Is the moment of misery systemic, or just an edge case? | _____ |
| Does the value proposition actually remove the obstacle? | _____ |

## 7. Finalized hypothesis _(complete in Module 3)_

> Based on [qual + quant evidence], I believe that [solving X] for [persona] will result in [outcome], as measured by a [X%] change in [success metric]. I will protect [guardrail metric] and make a go/no-go decision after [decision window].

## Link to full artifact

_[link to your Problem Hook Builder export]_
- **Value proposition:** The portal lets eligible payers choose an allowed collection date and see when the change takes effect. This gives them more control and can replace a manual support request.
- **Hypothesis:** # Hypothesis & Success Metrics

> **Module 3 · ★ Deliverable 3.** Repo file `03-analytics/hypothesis-and-metrics.md` — part of your submission.
> Do the lab in the **Module 3 · Exercise Guide** (linked from the Module 3 deck), then click **⬇ Download .md** — it saves as this exact file. Commit it here.
> It feeds the **Problem, Value & Hypothesis** slide of your Module 6 final deck.

## Finalized product hypothesis

> Based on [qual + quant evidence], I believe that [solving X] for [persona] will result in [outcome], as measured by a [X%] change in [success metric]. I will protect [guardrail metric] and make a go/no-go decision after [decision window].

## Success metrics

| Metric | Type | Target | Why it matters |
|---|---|---|---|
| _North-star_ | | _____ | _____ |
| _Leading indicator_ | | _____ | _____ |
| _Guardrail_ | | _____ | _____ |

### Slide 6 · Research
- **Competitive analysis:** # Competitive Analysis & Journey Map

> **Module 2 · Lab 2 — ★ Deliverable 2.** Repo file `02-discovery/competitive-and-journey.md` — part of your submission.
> Do the lab in the **Module 2 · Exercise 2 Guide** (linked from the Module 2 deck), then click **⬇ Download .md** — it saves as this exact file. Commit it here.
> It becomes the **Competitive Analysis & Journey Map** slide of your Module 6 final deck. Builds on your `ai-synthesis.md` and your Module 1 `problem-hook.md`.

## Responses

- **Role, who are you solving for?:** _(not filled in)_
- **Goal, what is this user ultimately trying to achieve?:** _(not filled in)_
- **Friction, the main barrier (moment of misery) stopping them:** _(not filled in)_
- **External tools the user is forced to use:** _(not filled in)_
- **The process, the 3–5 manual steps they take:** _(not filled in)_
- **Core frustration, where the process feels most "broken":** _(not filled in)_
- **The evidence, a quote or behavior from the research:** _(not filled in)_
- **Journey map, a shareable link or the map file you committed:** _(not filled in)_
- **Journey map:** Payer opens the portal → reviews the installment agreement and current collection date → needs a different date → cannot change it in self-service and contacts Support → waits for the request to be handled. The B2 flow intervenes when the payer reviews the current date: they choose an allowed date, see which installment will be affected, and confirm the saved change.

### Slide 7 · Blueprint
- **Roadmap:** # Roadmap, PRD & Prototype (Module 4)

## Deine strategischen Anker
- **Persona (M2), who are you solving for?:** A parent or self-paying customer who is financially responsible for a service and needs to understand exactly what the installment agreement covers.
- **Primary success metric (M3), your leading indicator:** A 20% relative reduction in the share of agreements with a post-creation manual contact tagged as a question about the payer, covered amount, or plan scope.
The current overall manual-contact rate is 14.6%, but it includes different reasons for contact. Tagging contact reasons will establish the relevant baseline.
- **Moment of misery (M2), the specific friction blocking the goal:** The financing journey becomes confusing when the real-world situation does not match the product's assumptions: the payer may not be the service recipient, the final amount may still change, or it may be unclear whether the plan covers the total treatment cost, a single invoice, or only a co-payment. The customer is forced to make a financial decision without a clear picture of what they are actually committing to.
- **Guardrail metric (M3), what must not drop or break:** The overall direct debit return rate and extension rate must not worsen by more than 2 percentage points compared with the baseline or a comparable control group.
Current overall reference rates are 13.00% for direct debit returns and 6.76% for extensions.

## Scanne den Rückstau und setze eine menschliche Basislinie
- **My instinctive “quick wins” before touching the AI (2 to 3 feature IDs + why):** _(not filled in)_

## Prüfen, überschreiben und entscheiden
- **Where did you override the AI? (feature + old vs. new score + why):** I raised B2 and B7 from Value 2 to 5 because they replace manual requests with simple portal actions. B1 went from 4 to 5, backed by customer uncertainty and plan changes in the data. I also raised B9 to 4 and lowered its effort to 2.For B3, B6, and B5, I increased value based on payment and adjustment needs, while raising effort to reflect the controls involved. I lowered B8’s effort because it uses the existing framework. B4 stays out of scope: useful, but complex and less tied to the main goal.
- **Did the AI over-value a Sales/Eng request your M2 interviews don’t support?:** No. B8 supports the roadmap but stays in Next. B4 has some user evidence, but it doesn’t outweigh the effort for this initiative.
- **Did it underweight something your M3 cohort/funnel data strongly supports?:** Yes. The extension, shortening, and returned-debit data make plan changes and payment support more important. They support prioritizing B1, B3, and B6, though they don’t prove those features will reduce contacts.

## Erstellen Sie Ihre interaktive Roadmap
- **My “Now” lane (this sprint), the 2 to 3 quick wins I’ll build first:** B2, B7, and B10. B2 and B7 let eligible payers handle common direct-debit changes in the portal; B10 establishes the measurement needed to track completions, abandonment, escalations, and contact reasons.
- **What I cut, and the “no” I’m protecting the scope from:** I cut B4 — Make an Extra Payment from this initiative. I’m protecting the scope from complex partial-payment allocation and recalculation, and from replacing core credit, risk, or servicing systems.
- **Prototype/roadmap screenshot link (paste into your deliverables):** _(not filled in)_
- **PRD highlights:** # PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The “Now” feature I’m scoping (name + one-line core description):** B2 — Change Direct-Debit Collection Date: Let an authorized payer change the collection date for an eligible installment agreement in the existing portal, using existing rules, and clearly see when the change takes effect.
- **My finalized Must-Haves (after overriding the AI):** B2 — Change Direct-Debit Collection Date: Let an authorized payer change the collection date for an eligible installment agreement in the existing portal, using existing rules, and clearly see when the change takes effect.
- **What I demoted from Must → Should/Won’t, and why:** Should: Explain why a date is unavailable and suggest a next step. Helpful, but not needed for a valid change.
Should: Track starts, completions, and failures through the shared B10 measurement work, rather than build separate analytics for B2.
Won’t now: Manage dates across multiple agreements, set a preferred date, or add a calendar view; these are V2 enhancements.
Won’t now: Change installment amounts or terms, defer a payment, update bank details, or replace core systems; those belong to other features or initiatives.

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** It tells the payer which installment will use the new collection date—and never shows success unless the change has actually been saved.

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** I needed to be clearer about which installment gets the new date, especially if a debit is already being processed. The prototype now shows the first affected installment before confirmation.
- **My prototype, as a link or a screenshot (publish or share from your tool; in Lovable that is Share → Share Preview, in Bolt Publish → Web. No share URL? Screenshot the working flow):** _(not filled in)_
- **Prototype:** https://chatgpt.com/c/6ac755de-c990-8336-ad0b-a684a74a2a39

### Slide 8 · Validation
# Experimentation Plan

> **Module 5 · ★ Deliverable 5.** Repo file `05-experimentation/experimentation-plan.md` — part of your submission.
> Do the lab in the **Module 5 · Exercise Guide** (linked from the Module 5 deck), then click **⬇ Download .md** — it saves as this exact file. Commit it here.
> It becomes the **Experimentation Plan** slide of your Module 6 final deck.

## Overview

_A high-level validation strategy to test your hypothesis before full-scale development._

_____

## What you're testing

| Element | Detail |
|---|---|
| Hypothesis under test | _____ |
| Experiment design (A/B, etc.) | _____ |
| Primary metric | _____ |
| Guardrail metric | _____ |
| Decision rule (ship / kill / pivot) | _____ |

## Findings & decision _(after running it)_

_____

### Slide 9 · Launch
- **GTM:** # Individual Insights: Development Process

> Module 6 · Launch Impactful GTM Plans, ★ Deliverable 6 (reflection)
>
> _The personal reflection that closes your final project._

## Friction points

_The biggest technical or strategic challenge you faced while developing your product concept._

_____

## Key learnings

_A few surprising discoveries or insights you gained from the course overall._

_____

## Aha! moment

_Your main "aha" moment during the project process._

_____
- **Metrics:** Primary: At least a 20% relative reduction in the share of assigned eligible payers with a collection-date-related manual contact within 30 days, compared with control; p < 0.05, two-sided.
Supporting: Completed self-service collection-date changes among eligible variant payers.
Guardrail: The direct-debit return rate must not exceed control by more than 2 percentage points.
Bad signal: Self-service changes increase but collection-date-related contacts do not fall, or the return-rate guardrail is breached. Any confirmed incorrect collection date means stop and investigate.

### Slide 10 · Story
- **Friction + aha:** The hardest part was connecting the original customer problem to B2. The broader problem is uncertainty about who pays and what the plan covers, while B2 addresses changing the collection date. The key insight was that the 14.6% contact rate covers all reasons, so it cannot prove demand for this specific feature. The test needs date-specific contact tagging.
- **Takeaways / next:** I would first establish the collection-date-specific baseline and recalculate the sample size. Then I would validate the portal flow with eligible payers, run the controlled pilot, and scale only if tagged contacts fall while direct-debit returns remain within the guardrail.

---

Submitted to the Product Management Certification learning platform · Product School.
