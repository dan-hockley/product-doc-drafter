# A/B Test Plan Template

### An A/B test plan defines the hypothesis, design, and success criteria for a controlled experiment. It gives engineers what they need to build the test, gives data what they need to measure it, and gives stakeholders enough detail to trust the result.

— [Delete above this line]

## [Test Plan Title]

**One-line Summary**
[What are we testing, where, and why. One sentence.

Example: "Testing a prominent annual plan upsell banner in the checkout flow to increase annual subscription take-up among new subscribers."]

**Initiative Link**
[Link to or name the 1-Pager or PRD this experiment supports. All test plans should connect to an initiative.]

### Hypothesis

[If we [make this change], then [this metric] will [increase / decrease / not change] because [reason].

Be specific and falsifiable. Avoid "we believe" or vague directional language.

Example: "If we display an annual plan comparison at the payment step, then annual plan selection rate will increase by at least 5 percentage points, because users who see the per-month cost comparison are more likely to choose the better-value option."]

### Background

[Why are we running this test now? What does the initiative PRD say about this experiment? What prior evidence, research, or data supports the hypothesis? Keep this concise - the PRD has the full context.]

### Variants

[Describe each variant clearly. Use a table. Include a brief description and note what is different from control.]

| Variant | Name | Description | What Changes vs. Control |
| :---- | :---- | :---- | :---- |
| Control | [Name] | [What the current experience looks like] | Baseline - no change |
| Variant A | [Name] | [What changes] | [Specific change from control] |
| Variant B (if applicable) | [Name] | [What changes] | [Specific change from control] |

### Audience

[Who is eligible for this test? Be precise.

- Which users are included (e.g. new visitors, logged-in subscribers, anonymous users on mobile web)?
- Which users are excluded and why?
- What is the expected eligible audience size per week?]

### Traffic Split

[What percentage of eligible traffic goes to each variant, and why?

Example: "50/50 split between control and variant A. No holdout - full rollout on win."]

### Success Metrics

[One primary metric only. Secondary and guardrail metrics listed separately.]

| Type | Metric | Definition | Baseline | Target |
| :---- | :---- | :---- | :---- | :---- |
| **Primary** | [Metric name] | [How it is calculated] | [Current value] | [Expected lift] |
| **Secondary** | [Metric name] | [How it is calculated] | [Current value] | [Direction] |
| **Secondary** | [Metric name] | [How it is calculated] | [Current value] | [Direction] |
| **Guardrail** | [Metric name] | [How it is calculated] | [Current value] | Must not decrease |
| **Guardrail** | [Metric name] | [How it is calculated] | [Current value] | Must not decrease |

[Guardrails are metrics you commit to not harming. If a guardrail is breached, the test is stopped regardless of primary metric performance.]

### Sample Size and Duration

**Metric definition**
- Numerator: [What is being counted in the numerator - e.g. users who completed a subscription]
- Denominator: [The eligible population - e.g. unique users who saw the paywall]
- Unit of randomization: [User / session / other - must match the metric unit]

**Calculation inputs**
- Baseline rate: [Current value of the primary metric]
- Minimum detectable effect (MDE): [Absolute lift - e.g. +1 percentage point]
- Relative MDE: [MDE as a % of baseline - e.g. 10%]
- Statistical significance: [95% two-tailed]
- Statistical power: [80%]
- Traffic split: [50/50 or other]

**Sample size calculation**
[Show the formula and inputs used. Anyone should be able to replicate this from what is written here.]

- Required sample per variant: [N users]
- Weekly eligible users: [N]
- Estimated test duration: [X weeks]

**Assumptions and caveats**
[List any assumptions behind the estimate. Flag if baseline data is unavailable or if the duration is uncertain.]

### Risks and Mitigations

[What could go wrong? Be specific - not generic.]

| Risk | Likelihood | Mitigation |
| :---- | :---- | :---- |
| [Risk description] | High / Medium / Low | [How we reduce or manage it] |

### Stakeholder Questions

[Only include if there are genuine unresolved questions. Remove this section if none. Any claim without data backing must become a question here - not a TBD or blank.]

### Results

[Filled in after the test concludes. Leave blank until then.]

**Test ran:** [Start date] to [End date]
**Result:** [Winner / No significant difference / Stopped early]
**Primary metric outcome:** [What happened]
**Decision:** [Ship variant / Revert to control / Run follow-up test]
**Key learnings:** [What we learned that informs future work]
