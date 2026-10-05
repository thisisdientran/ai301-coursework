# Evidence guide: where proof lives in a reproduction package
## Family 1: is it show environment?
Where it lives: In an eval bundle, check the issue context for the versions and platforms named by the issue, then compare them with the repo-facts block and the environment details in the repro report. In live mode, check the issue thread, the repository’s setup or support documentation, and the student’s draft comment.

What good looks like: The report identifies the relevant operating system, runtime, dependency, browser, database, or configuration details needed to reproduce the issue. The versions named match the issue’s target, or any difference is explicitly called out.

## Family 2: is it demonstrated steps?
Where it lives: In an eval bundle, check the reproduction steps in the repro report, including its starting state, commands, inputs, and trigger. In live mode, check the student’s draft comment against the issue thread and the repository’s installation, setup, and contribution documentation.

What good looks like: A stranger can begin from the stated starting state and follow the steps in order without guessing missing commands, files, inputs, permissions, or configuration. The final step clearly identifies the action that triggers the reported behavior.

## Family 3: is it show behaviors?
Where it lives: In an eval bundle, check the output excerpts, logs, screenshots, recordings, test results, and other artifacts attached to the repro report. Compare them with the issue’s expected and observed behavior. In live mode, check the evidence linked or pasted in the student’s draft comment and compare it with the behavior described in the issue thread.

What good looks like: The artifact visibly or textually shows the reported behavior occurring after the documented trigger. It distinguishes the issue from an adjacent warning, unrelated error, expected limitation, or different failure mode, and includes enough surrounding context to connect the artifact to the reproduction steps.

## Family 4: Honesty
Where it lives: In an eval bundle, compare the claim comment with the issue context, repo-facts block, reproduction steps, and behavior artifacts. In live mode, compare the student’s draft comment with the issue thread, repository documentation, and the evidence they actually collected.

What good looks like: Each claim is limited to what the evidence supports. The report separates observed facts from interpretation, identifies uncertainty and scope, and says clearly when the issue could not be reproduced instead of presenting a related result as proof.

## Family 5: Comms
Where it lives: In an eval bundle, check the claim comment and compare it with the issue’s requested format, the repository’s issue or contribution templates, relevant documentation, and any AI-use disclosure requirements. In live mode, check the student’s draft comment against the GitHub issue thread, repository docs, templates, contribution policy, and disclosure rules.

What good looks like: The comment is specific, readable, and organized around the repository’s expected format. It states the environment, steps, observed behavior, evidence, scope, and limitations without boilerplate, and includes any required AI-use disclosure accurately and visibly.
