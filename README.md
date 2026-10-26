# AML Case Replay Test

A low-cost way to test whether the information on an alert screen is enough to reach a sound decision. No software needed.

## The idea

If a colleague who has never seen a case can predict its outcome from the alert screen alone, the screen is doing its job. If they cannot, information is missing at the point of review.

## Method

1. Pick one alert type.
2. Choose 10 closed cases with a mix of outcomes.
3. For each, recreate exactly what the investigator saw when the alert opened. Do not include later findings or the case notes.
4. Give each recreation to a colleague who has not seen the case.
5. Ask them two questions:
   - What would you decide, and why?
   - What would you want to look up first?
6. Record answers in `case-log-template.csv`.
7. Compare predictions with actual outcomes.

## Reading the results

- **Prediction matches outcome:** the screen supported the decision.
- **Prediction differs from outcome:** something relevant was missing at the screen.
- **"Look up first" answers:** your requirements list. Count how often each item appears.

## Caution

A small sample shows direction, not proof. Repeat with a different alert type before changing your process, and keep the results for your quality review.

## Background

- Full analysis: https://technoxander.com/aml-alerts-missing-context-financial-crime/
- Why prior cases get lost: https://technoxander.com/organisational-memory-aml-ai-investigations/

## Licence and disclaimer

CC BY 4.0. Maintained by TechnoXander. General information, not legal or regulatory advice.
