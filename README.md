# Neal Shandilya

I’m a founding engineer at [Millennium Research](https://www.millenniumresearch.ai/).
I lead work on the Legatus loop: a coding agent writes a program and its
specification, checks them with a verifier, and uses the feedback to try again.

I’m also designing release checks for the graders that score AI agents. If a
grader update starts accepting a wrong outcome or rejecting a valid one, I want
the reviewer to have the exact case they can replay.

Explore [research & tools](https://nealyx.github.io/)
for a guided tour, or reach me at [neal@millenniumresearch.ai](mailto:neal@millenniumresearch.ai).

## Start with these projects

| Project | What to explore | What is available |
|---|---|---|
| **[ReviewOps](https://github.com/nealyx/reviewops)** | What changed between evidence snapshots and which version was reviewed | A local prototype with revision comparison, portable review summaries, offline backup/restore, and synthetic cases |
| **[Math Reward Hacking](https://github.com/nealyx/math-reward-hacking)** | How completion limits and answer extraction change an apparent training result | 10,500 saved completions, a worked example, analysis, and verification commands |

To try the workflow tool, download the
[ReviewOps release](https://github.com/nealyx/reviewops/releases/latest).
Compare revisions, inspect evidence, and download a readable review summary.
Offline backups preserve the complete workspace.
It runs locally with Python and no third-party packages.

For a saved-output research example, read the
[math case study walkthrough](https://github.com/nealyx/math-reward-hacking/blob/main/docs/walkthrough.md).
It follows one saved response through different scoring rules and explains why
the study does not establish consistent reward hacking.

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
