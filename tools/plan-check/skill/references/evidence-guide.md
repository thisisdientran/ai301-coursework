# Evidence guide: where evidence lives in a plan package

## Diagnosis and grounding

**Where it lives:**
- Eval mode: candidate plan's diagnosis and repro-evidence block.
- Live mode: draft plan and the student's posted reproduction evidence.

**What good looks like:**
The plan states at least one clear root cause, and that cause explains the behavior shown by the reproduction. The diagnosis should not contradict the reproduction evidence.

## Scope

**Where it lives:**
- Eval mode: candidate plan's scope section and issue context.
- Live mode: draft plan's scope section and GitHub issue description.

**What good looks like:**
The plan clearly identifies what is in scope or what is not in scope. The planned work stays focused on the issue instead of adding unrelated changes.

## Executability

**Where it lives:**
- Eval mode: candidate plan's files and approach sections.
- Live mode: draft plan and repository file paths.

**What good looks like:**
The plan names at least one specific file or file path and at least one concrete implementation step. Another developer should be able to understand where to start and what change to make.

## Test plan

**Where it lives:**
- Eval mode: candidate plan's test-plan section and repro-evidence block.
- Live mode: draft plan's test section and posted reproduction.

**What good looks like:**
The plan includes at least one specific test or command and one expected result. The test should demonstrate whether the reproduced problem is fixed.

## Honesty

**Where it lives:**
- Eval mode: candidate plan's risks, unknowns, and deviations sections.
- Live mode: draft plan's risks and deviations.

**What good looks like:**
Unknown behavior or risks are stated instead of being presented as confirmed facts. If implementation changes from the original plan, the difference should be recorded as a deviation.

## Comms

**Where it lives:**
- Eval mode: plan comment, issue context/thread, and repo-facts contribution policy.
- Live mode: proposed plan comment, GitHub issue thread, CONTRIBUTING.md, and any AI-use policy.

**What good looks like:**
The plan comment follows relevant maintainer guidance when guidance exists and promises only work contained in the plan. It should also follow any contribution or AI-disclosure requirements stated by the repository.