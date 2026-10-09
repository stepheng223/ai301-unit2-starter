# Evidence guide: where proof lives in a reproduction package

Read the whole issue context, claim, and report before grading. Eval mode uses only the frozen bundle, including repo facts and thread highlights; never open the live source issue. Live mode first confirms scope, then reads the issue body/thread, repository bug-report templates, CONTRIBUTING.md and linked policies, and draft comments. Do not silently supplement posted drafts with local files readers cannot see.

## Environment

Where it lives: the report's environment paragraph, version output and build/setup commands, compared with issue context and repo-facts reporting asks. Live mode uses the corresponding draft, issue and repository instructions.

What good looks like: explicit tested version and platform, plus installation method or build profile when required or relevant. Identify differences from the reporter and limit conclusions accordingly. A debug panic may match an issue that describes both debug panic and release hang, but does not establish an unstated version or platform.

## Steps

Where it lives: report setup, inline input files, commands, UI actions, and actual accessible artifact contents. Compare with the issue's minimal trigger; live mode uses the same parts of the draft and issue.

What good looks like: enough starting state, data and actions to execute without guessing. One complete command can suffice. A filename without necessary contents, missing attachment, or unspecified setup leaves a gap. Do not impose a step count or headings.

## Behavior shown

Where it lives: issue body/thread trigger and distinctive symptom, compared with report output excerpts, logs, visible screenshots or concrete expected/actual observations. Live mode uses the issue and supplied drafts in the same way.

What good looks like: the input reaches the intended trigger and the artifact shows the reported symptom or a clearly bounded inability to reproduce it. Match error text and output semantics, not broad categories like failure. Invalid syntax rejected before execution does not reproduce a panic on valid input. Repeating the wrong trigger does not repair the mismatch. A successful execution supports cannot-reproduce when the relevant trigger and actual result are documented.

## Honesty

Where it lives: factual assertions in the claim, report analysis/conclusion, and backing inputs, artifacts and environment. Live mode reads submitted claim and report together; claim-only future plans are promises rather than observations.

What good looks like: distinguish observations, hypotheses and next actions. A limited negative result documents an attempt, not proof the original issue is false. Unsupported certainty about cause, other versions or a fix fails conclusion-supported. Do not demand reproduction artifacts for work merely promised in a claim-only draft.

## Comms

Where it lives: claim against issue body/thread; both comments against repo-facts template and policy fields. Live mode reads the issue thread, .github/ISSUE_TEMPLATE, CONTRIBUTING.md and linked AI-use policy. Personal voice-guide.md is live-only feedback.

What good looks like: an issue-specific claim and concrete next action, respectful understandable prose, and substantive reporting asks met. Independent testing is useful when a reporter already has a fix. Under Path Review house rules, a classmate's claim is not a blocker. Required AI disclosure must be explicit; do not invent a requirement when policy is silent. Formatting cannot compensate for evidence of a different bug.

For each grade cite a decisive quote or fact and its section. If evidence is absent, name what is missing. Inaccessible live sources produce unclear for dependent checks, never invented passes.
