# PRD & Prototype Sprint (Module 4)

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
