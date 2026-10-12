# A/B Experiment Brief, Riverty business-unit case

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | B2 — Change Direct-Debit Collection Date: Let eligible Responsible Payers change the collection date in the existing portal and see when the change takes effect. |
| Persona | A parent or self-paying customer who is financially responsible for a service and needs to understand exactly what the installment agreement covers. |
| Expected outcome | More eligible payers complete a collection-date change in self-service, with fewer collection-date-related manual contacts and no deterioration in payment reliability. |
| Primary success metric | Share of eligible agreements with a manual contact tagged as a collection-date-change request within 30 days of experiment assignment. Target: 20% relative reduction in the variant versus control. Track completed self-service date changes as a supporting signal. |
| Baseline rate | 14.6% overall post-creation manual-contact rate, for planning only. This includes all contact reasons; establish a collection-date-specific baseline before interpreting results. |
| Guardrail metric | Direct-debit return rate. |
| Guardrail boundary | No statistically credible increase versus control. Hard stop at +2 percentage points; using the current 13.00% overall reference rate, that is 15.00%. Existing eligible agreement extensions and shortenings must remain possible. |
| Second guardrail | None for this test; keep the guardrail focused on payment reliability. |
| Minimum Detectable Effect | 2.9 percentage points, based on a 20% relative reduction from the 14.6% planning proxy. |
| Sample size per arm | Approximately 2,100 eligible agreements per arm, assuming 80% power and a 5% significance level. Recalculate once the collection-date-specific baseline is known. |
| Traffic split | 50% control / 50% variant. |
| Test duration | Run until the required sample is reached and both groups have completed at least two full collection cycles. Do not make a final call before then. |
| Significance threshold | p < 0.05, two-sided; 80% power. |

## Control vs. Variant
- **Control (A):** Eligible payers can see their installment agreement in the portal, but they cannot change the direct-debit collection date there. To request a change, they contact support. M3 shows that 46.2K of 316K agreements (14.6%) have a post-creation manual contact overall; the collection-date-specific baseline still needs to be measured.
- **Variant (B):** Add the B2 collection-date change flow to the existing portal. The entry screen shows the current date. The payer can choose from dates permitted by existing rules and see which installment will be affected before confirming. A confirmation screen appears only after the change is saved. The installment amount and agreement term remain unchanged.
- **Held constant (isolation check):** Both groups use the same portal, eligible-payer criteria, date rules, agreement terms, installment amounts, direct-debit process, notifications, and support service. The only experience difference is that Variant B lets eligible payers change the collection date in the portal. Apply the same measurement and contact-reason tagging to both groups.

## Hypothesis
> I believe that B2 — Change Direct-Debit Collection Date: Let eligible Responsible Payers change the collection date in the existing portal and see when the change takes effect. for A parent or self-paying customer who is financially responsible for a service and needs to understand exactly what the installment agreement covers. will result in More eligible payers complete a collection-date change in self-service, with fewer collection-date-related manual contacts and no deterioration in payment reliability., as measured by a 2.9 percentage points, based on a 20% relative reduction from the 14.6% planning proxy. change in Share of eligible agreements with a manual contact tagged as a collection-date-change request within 30 days of experiment assignment. Target: 20% relative reduction in the variant versus control. Track completed self-service date changes as a supporting signal. within Run until the required sample is reached and both groups have completed at least two full collection cycles. Do not make a final call before then.. We will protect Direct-debit return rate. throughout the test.

## Shipping criteria
> We will **ship** if Share of eligible agreements with a manual contact tagged as a collection-date-change request within 30 days of experiment assignment. Target: 20% relative reduction in the variant versus control. Track completed self-service date changes as a supporting signal. improves by ≥ 2.9 percentage points, based on a 20% relative reduction from the 14.6% planning proxy. at p < 0.05, two-sided; 80% power. and Direct-debit return rate. does not reach No statistically credible increase versus control. Hard stop at +2 percentage points; using the current 13.00% overall reference rate, that is 15.00%. Existing eligible agreement extensions and shortenings must remain possible. after Run until the required sample is reached and both groups have completed at least two full collection cycles. Do not make a final call before then..
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of Run until the required sample is reached and both groups have completed at least two full collection cycles. Do not make a final call before then., no results reviewed before this date.
