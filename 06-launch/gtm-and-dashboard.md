# GTM Launch Plan, Riverty business-unit case

| Field | Value |
|---|---|
| Feature | B2 — Change Direct-Debit Collection Date: Eligible payers can change their collection date in the existing portal and see which installment will be affected. |
| Goal | Conversion |
| Launch tier | M, Targeted |

## Goal & Audience
- **Goal:** Conversion, This feature is intended to change a measurable customer action: eligible payers completing a collection-date change in self-service. The pilot will measure completed changes and collection-date-related support contacts.
- **Target audience:** Existing Responsible Payers with an active installment agreement and portal access, whose agreement meets the existing rules for changing the collection date. Do not target all patients or all customers.

## Launch Tier
- **M, Targeted**, _(not filled in)_

## Channels
1. **Owned: In-portal entry point on the installment agreement page, shown to eligible payers in the variant.**
2. **Owned: Help-centre article and support guidance explaining eligibility, the effective date, and that installment amounts and agreement terms do not change. Make the guidance available consistently to both groups.**
3. **Owned: Targeted email to eligible payers after the experiment meets its success criteria and the feature is approved for broader rollout.**

## Enablement & Assets
Create a short payer FAQ, support response template, and internal one-page guide. Explain who is eligible, how to choose an allowed date, which installment is affected, and when the change takes effect. State clearly that the installment amount and agreement term remain unchanged. Brief Support before the pilot.

## Ownership, Budget & Timeline
- **Ownership & budget:** Product Manager owns the launch plan, experiment setup, and go/no-go recommendation. Product Designer owns portal copy and flow. Engineering Lead owns implementation and event tracking. QA Owner verifies eligibility, date rules, and confirmation after save. Support Owner prepares the FAQ and response template. Use existing team capacity; no paid-media budget is planned.
- **Timeline:** Pre-launch: confirm the collection-date contact tagging, establish the date-specific baseline, recalculate the sample size, and prepare Support. Pilot: release the portal flow to the variant in a 50/50 experiment. Keep enrollment open until the required sample is reached; wait until both groups have completed at least two full collection cycles before the final readout. After the readout: scale gradually if the success criteria are met; otherwise investigate, iterate, or stop.

## Success Metrics
- **Metrics:** Primary: at least a 20% relative reduction in the share of assigned eligible payers with a collection-date-related manual contact within 30 days, compared with control.  
Supporting: completed self-service collection-date changes among eligible variant payers.  
Guardrail: direct-debit return rate must not exceed control by more than 2 percentage points.
- **Bad signal to watch for:** Self-service changes increase but collection-date-related contacts do not fall, or the direct-debit return rate exceeds the +2 percentage-point guardrail. Any incorrect collection date applied is a critical issue.
- **Likely post-launch decision:** If the primary metric reaches the 20% relative reduction target with p < 0.05 and the guardrail holds, scale gradually. If results are inconclusive but the guardrail holds, review the baseline, sample size, and funnel before extending or iterating. If the guardrail is breached or an incorrect date is applied, stop the rollout and investigate.
