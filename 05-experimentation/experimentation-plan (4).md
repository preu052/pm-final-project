# A/B Experiment Brief, Riverty business-unit case

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | B2 — Change Direct-Debit Collection Date: Let eligible payers change the collection date in the existing portal and see when the change takes effect. |
| Persona | A parent or self-paying customer who is financially responsible for an installment agreement. |
| Expected outcome | More eligible payers complete collection-date changes in self-service, and fewer contact support about changing their collection date. |
| Primary success metric | Share of assigned eligible payers with at least one manual contact tagged as a collection-date-change request within 30 days of assignment. Compare variant with control. |
| Baseline rate | Share of assigned eligible payers with at least one manual contact tagged as a collection-date-change request within 30 days of assignment. Compare variant with control. |
| Guardrail metric | Direct-debit return rate. |
| Guardrail boundary | The variant must not exceed the control by more than 2 percentage points. |
| Second guardrail | - |
| Minimum Detectable Effect | 2.9 percentage points, provisional; based on a 20% relative reduction from the 14.6% planning proxy. Recalculate using the collection-date-specific baseline before launch. |
| Sample size per arm | 2,514 eligible payers per group, provisional; recalculate once the collection-date-specific baseline is known. |
| Traffic split | 50% control / 50% variant. |
| Test duration | Run until the required sample is reached and both groups have completed at least two full collection cycles. Measure the primary metric within 30 days of assignment. |
| Significance threshold | p < 0.05, two-sided. |

## Control vs. Variant
- **Control (A):** Eligible payers can view their installment agreement in the portal but cannot change the direct-debit collection date there. They must contact support to request a change. M3 shows that 46.2K of 316K agreements (14.6%) have a post-creation manual contact overall. This includes all contact reasons; the collection-date-specific baseline is not yet known.
- **Variant (B):** Add the B2 collection-date change flow to the existing portal. Show the current collection date, let eligible payers select a date permitted by existing rules, and show which installment will be affected before they confirm. Show confirmation only after the change has been saved. The installment amount and agreement term remain unchanged.
- **Held constant (isolation check):** Both groups use the same portal, eligibility criteria, date rules, agreement terms, installment amounts, direct-debit process, standard notifications, and support service. Use the same contact-reason tagging and measurement in both groups. Keep all eligible agreements belonging to one payer in the same group. The only difference is that Variant B lets eligible payers change the collection date in the portal.

## Hypothesis
> I believe that B2 — Change Direct-Debit Collection Date: Let eligible payers change the collection date in the existing portal and see when the change takes effect. for A parent or self-paying customer who is financially responsible for an installment agreement. will result in More eligible payers complete collection-date changes in self-service, and fewer contact support about changing their collection date., as measured by a 2.9 percentage points, provisional; based on a 20% relative reduction from the 14.6% planning proxy. Recalculate using the collection-date-specific baseline before launch. change in Share of assigned eligible payers with at least one manual contact tagged as a collection-date-change request within 30 days of assignment. Compare variant with control. within Run until the required sample is reached and both groups have completed at least two full collection cycles. Measure the primary metric within 30 days of assignment.. We will protect Direct-debit return rate. throughout the test.

## Shipping criteria
> We will **ship** if Share of assigned eligible payers with at least one manual contact tagged as a collection-date-change request within 30 days of assignment. Compare variant with control. improves by ≥ 2.9 percentage points, provisional; based on a 20% relative reduction from the 14.6% planning proxy. Recalculate using the collection-date-specific baseline before launch. at p < 0.05, two-sided. and Direct-debit return rate. does not reach The variant must not exceed the control by more than 2 percentage points. after Run until the required sample is reached and both groups have completed at least two full collection cycles. Measure the primary metric within 30 days of assignment..
> We will **iterate** if direction is positive but lift is below the MDE.
> We will **kill** if the primary metric shows no improvement or moves negatively.
> The read date is fixed at the end of Run until the required sample is reached and both groups have completed at least two full collection cycles. Measure the primary metric within 30 days of assignment., no results reviewed before this date.
