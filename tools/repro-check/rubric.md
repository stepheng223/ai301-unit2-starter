# Rubric: is this reproduction package ready to post?

## Checks

| Check | Evidence | Pass condition | Weight |
|---|---|---|---|
| claim-specific | Claim compared with issue body and thread highlights. | Names the particular trigger or symptom and a concrete next action. Acknowledges existing work when it affects that action. Generic enthusiasm alone fails; another student's claim does not block independent testing. | required |
| environment-recorded | Report's environment and version output compared with issue and repo reporting asks. | Explicitly records tested software version and platform, plus installation method or build details when requested or material. Identifies differences from the issue environment and limits conclusions accordingly. Do not infer missing versions from the issue or latest release. | required |
| steps-rerunnable | Report setup, supplied input, commands or UI actions, and artifact contents. | A stranger can reach the starting state and execute the trigger without inventing necessary details. A minimal command can suffice. Missing input files, empty artifact placeholders, or inaccessible links without usable inline evidence fail. | required |
| behavior-matches-issue | Issue trigger and distinctive symptom compared with report's actual output, logs, visible screenshots, or concrete observed result. | Evidence tests the relevant trigger and demonstrates the issue's distinctive behavior, or a bounded cannot-reproduce result from a valid attempt at that trigger. An adjacent error, malformed substitute input, or unsupported assertion of reproduction fails. Artifact labels alone are not evidence. | required |
| conclusion-supported | Claim factual assertions and report conclusion compared with supplied inputs, artifacts, and environment. | Claims stay within the supplied evidence. Honest cannot-reproduce passes with a valid attempt and actual result. Unsupported claims of root cause, fixes, exact reproduction, or cross-version coverage fail. Future plans do not require completed reproduction evidence. | required |
| repo-conventions | Both comments compared with repo-facts reporting asks and contribution policy. | Supplies required substantive reporting information in understandable, respectful prose, including AI disclosure when policy requires it. Equivalent prose satisfies templates; headings alone do not. No AI disclosure is required when the policy is silent. | required |

## Verdict rule

Grade pass, fail, or unclear. Fail means a visible contradiction or unmet requirement; unclear means necessary evidence is absent. Accept (ready) only when every applicable required check passes; otherwise reject (hold). Unclear counts as fail. Preferred checks, if added, never affect the verdict.

For claim-only drafts, apply claim-specific, repo-conventions to claim-applicable conventions, and conclusion-supported to claim factual assertions only. Mark environment-recorded, steps-rerunnable, and behavior-matches-issue unclear with evidence `not yet applicable: claim-only draft`, excluding these three from the verdict. Report-template asks do not apply yet. Full packages apply every check. Personal voice rules provide live feedback without independently changing the verdict.
