# Roadmap, PRD & Prototype (Module 4)

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
