# Learning-system architecture

## Design objective

Convert AI-generated explanation into a system that supports understanding, retrieval, transfer, and targeted repair.

## Six stages

| Stage | Learner action | AI or material responsibility | Failure signal |
|---|---|---|---|
| See | Inspect the mechanism or example | Make the relevant structure visible | Learner can name terms but cannot point to the mechanism |
| Build | Reconstruct the mental model | Start from first principles and dependencies | Explanation depends on memorized wording |
| Connect | Link the model to an exact rule | State assumptions, units, and boundary cases | Formula is recalled without conditions |
| Solve | Transfer to a direct, disguised, or mixed problem | Fade support and expose decisions | Learner copies a procedure but cannot choose it |
| Retrieve | Rebuild without the source | Prompt closed-book reconstruction | Familiarity is mistaken for recall |
| Repair | Fix the failed dependency | Diagnose before recommending repetition | Whole-topic replay replaces targeted work |

## Content unit specification

Each concept unit should contain:

1. the problem that made the idea necessary;
2. one explanatory visual or trace;
3. an exact rule in plain language and notation;
4. one worked example with decisions exposed;
5. one nearby problem with reduced help;
6. one unsupported transfer problem;
7. one closed-book retrieval prompt;
8. a likely-error map and targeted repair.

## Help-fading policy

Support should decrease only after the learner can explain the prior step. A useful sequence is:

1. fully worked example;
2. completion problem with missing steps;
3. hint on demand;
4. independent problem;
5. mixed problem where the method is not named.

## Retrieval policy

Rereading is not evidence of ownership. Use retrieval before reopening material:

- immediately after the concept;
- later the same day;
- after 24 hours;
- after 7 days;
- inside a mixed set.

The exact spacing may change, but the principle remains: inspect the failed reconstruction, not the learner’s feeling of familiarity.

## Repair policy

A repair should be smaller than the original lesson whenever possible. Reopen only the missing definition, assumption, dependency, or decision rule, then verify on a different problem.
