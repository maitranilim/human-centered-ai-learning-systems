# Public methods release: evidence-gated learning system

This is a compact, runnable version of the recurring system used to design the private learning artifacts. It is intended for an educator, tutor, or AI product team to adapt.

## Inputs

Prepare:

1. the learner's target and current constraints;
2. the official topic or task scope;
3. one representative problem or performance attempt;
4. an explanation-quality rubric;
5. a small set of retrieval and transfer questions.

## Run the loop

1. **See the mechanism.** Start with the smallest picture, example, or state change that makes the topic observable.
2. **Build the model.** Name the objects, dependencies, assumptions, and boundaries.
3. **Connect the rule.** State the exact relationship and when it does not apply.
4. **Solve under pressure.** Use one worked example, then fade help on a nearby problem.
5. **Retrieve without help.** Close the material and reconstruct the idea in plain language or a diagram.
6. **Repair the diagnosed gap.** Classify the failure, apply the smallest repair, and retest with an isomorphic problem.

## Evidence gates

Do not advance because a calendar says so or because the explanation feels familiar. Advance only when the learner can:

- explain the mechanism without copying;
- state the rule with assumptions and boundary conditions;
- transfer it to a nearby problem;
- retrieve the core idea after a delay;
- identify the failed dependency when performance breaks.

## Cost-control rule

Do not regenerate or replay the whole lesson when one diagnostic identifies a narrow gap. Reuse the accepted explanation, visual, and question skeleton. Change only the failed component, then compare the before and after result.

## Output record

For each session, record:

| Field | Minimum evidence |
|---|---|
| Learner problem | One observable failure or decision |
| Human direction | The constraint, critique, or acceptance rule |
| AI behavior before | What was shallow, wrong, decorative, or unsafe |
| Change | The revised prompt, rubric, visual, or workflow |
| Retest | A nearby problem or reconstruction task |
| Limit | What remains unmeasured or context-dependent |

Use the [session brief](../templates/learning-session-brief.md), [error ledger](../templates/error-ledger.md), and [exit gate](../templates/exit-gate.md) to make the workflow repeatable.

## Limits

This method demonstrates operational design. It does not establish causal improvement in score, retention, motivation, or completion. Verify technical content against authoritative sources, and run an appropriate learner evaluation before making outcome claims.
