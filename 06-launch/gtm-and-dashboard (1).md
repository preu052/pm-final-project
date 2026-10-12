# GTM Launch Plan, Riverty business-unit case

| Field | Value |
|---|---|
| Feature | B2 — Change Direct-Debit Collection Date: Eligible payers can change their collection date in the existing portal and see which installment will be affected. |
| Goal | Conversion |
| Launch tier | M, Targeted |

## Goal & Audience
- **Goal:** Conversion, Move eligible collection-date changes from manual support to self-service. The pilot will test whether the portal flow reduces collection-date-related contacts by at least 20% relative to control, while tracking completed self-service changes and protecting payment reliability.
- **Target audience:** Existing Responsible Payers with an active installment agreement and portal access, whose agreement meets the existing rules for changing the collection date. Target eligible payers only; do not target all patients or customers.

## Launch Tier
- **M, Targeted**, The feature uses the existing portal and date rules, but it can affect payment collection. A targeted 50/50 pilot allows BFS to measure impact and payment reliability before a broader rollout. Confirm that the eligible audience can reach the required sample before setting the launch date.

## Channels
1. **Owned: In-portal entry point on the installment agreement page, shown only to eligible payers in the variant during the experiment.**
2. **Owned: Internal Support guidance on eligibility and how to handle questions. Keep customer-facing help-centre content and support guidance unchanged during the experiment; do not proactively promote the new flow.**
3. **Owned: Targeted email to eligible payers after the experiment meets its success criteria and the feature is approved for rollout. Do not send this email during the A/B test.**

## Enablement & Assets
Before the pilot, prepare an internal payer FAQ, a support response template, and a one-page guide for Support. Cover eligibility, allowed dates, the affected installment, and when the change takes effect. State that the installment amount and agreement term remain unchanged. After the experiment, adapt the FAQ for the help centre and prepare the rollout email.

## Ownership, Budget & Timeline
- **Ownership & budget:** Product Manager: owns the launch plan, experiment setup, metric review, and go/no-go recommendation. Product Designer: owns portal copy and flow. Engineering Lead: owns implementation and event tracking. QA Owner: verifies eligibility, date rules, and confirmation after save. Support Owner: prepares the FAQ and response template. Use existing team capacity; no paid-media budget is planned. Confirm team capacity before launch.
- **Timeline:** Pre-launch: assign owners, verify contact-reason tagging in both groups, establish the collection-date-specific baseline, recalculate the sample size, and prepare Support. Pilot: release the portal flow to the variant in a 50/50 experiment and continue enrollment until the recalculated sample is reached. Readout: wait until each group has completed at least two full collection cycles and the primary metric’s 30-day window has elapsed. After readout: scale gradually if the success criteria are met; otherwise investigate, iterate, or stop.

## Success Metrics
- **Metrics:** Primary: at least a 20% relative reduction in the share of assigned eligible payers with a collection-date-related manual contact within 30 days, compared with control. Require p < 0.05, two-sided.
Supporting: completed self-service collection-date changes among eligible variant payers.
Guardrail: the direct-debit return rate must not exceed control by more than 2 percentage points.
- **Bad signal to watch for:** Self-service changes increase but collection-date-related contacts do not fall, suggesting the flow is adding a channel rather than replacing support requests. The direct-debit return rate exceeds the +2 percentage-point guardrail. Any confirmed incorrect collection date is a critical issue.
- **Likely post-launch decision:** If the primary metric reaches the 20% relative reduction target with p < 0.05 and the guardrail holds, scale gradually. If results are inconclusive but the guardrail holds, review the baseline, sample size, and funnel before extending or iterating. If the guardrail is breached or an incorrect date is applied, stop the rollout and investigate.
