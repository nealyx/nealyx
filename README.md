# Neal Shandilya

I work on mathematical evaluation, research tooling, and the gap between a
measurement and the claim made from it.

My current projects ask practical questions: Does a reward measure the behavior
we intended? What information does a learned representation retain? Can another
person inspect the evidence behind an experiment and understand its limits?

## Start with these projects

| Project | What to explore | What is available |
|---|---|---|
| **[Math Reward Hacking](https://github.com/nealyx/math-reward-hacking)** | How completion limits and answer extraction change an apparent training result | 10,500 saved completions, a worked example, analysis, and verification commands |
| **[ReviewOps](https://github.com/nealyx/reviewops)** | Evidence handoffs, review decisions, and retained experiment revisions | A local Python app with synthetic examples and behavior tests; researcher pilot pending |
| **[EGRA FACED](https://github.com/nealyx/egra-faced)** | Separating stimulus identity, subject/session identity, and individual response in EEG representations | Saved predictions, controls, methods, and a dependency-free result verifier |
| **[Multimodal Response Lab](https://github.com/nealyx/multimodal-response-lab)** | A signal-processing workflow from structured observations to inspectable reports | A camera-free synthetic walkthrough plus optional live capture; no validated cognitive-state claims |

For a quick first look, read the
[math case study walkthrough](https://github.com/nealyx/math-reward-hacking/blob/main/docs/walkthrough.md).
It follows one saved response through different scoring rules and explains why
the study does not establish consistent reward hacking.

To try the workflow tool, download the
[ReviewOps release](https://github.com/nealyx/reviewops/releases/latest).
It runs locally with Python and no third-party packages.

## Research in progress

[Formalization evaluation robustness](https://github.com/nealyx/formalization-eval-robustness)
is a **documentation scaffold** for testing whether equivalent mathematical
presentations change an evaluator's verdict. The public branch explains the
question and proposed controls; it does not contain a runnable experiment or
reported findings.

## How to read this portfolio

Each featured repository explains what runs, where the evidence comes from, and
what remains unverified. Saved-output reproduction is distinguished from
regenerating an experiment; synthetic demonstrations are labeled as such.
I use AI-assisted engineering, and treat tests, source inspection, and explicit
limits as necessary parts of making the work reviewable.

Forks have their own upstream authors. My
[LeanScreen fork](https://github.com/nealyx/leanscreen) comes from
[ibrahimmian36/leanscreen](https://github.com/ibrahimmian36/leanscreen), and my
[USAMO Guide fork](https://github.com/nealyx/usamo-guide) comes from
[usamoguide/usamo-guide](https://github.com/usamoguide/usamo-guide).
They are separate from the original projects featured above.
