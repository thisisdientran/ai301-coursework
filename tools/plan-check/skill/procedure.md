# Procedure: how this skill grades a plan package

## Read order

1. Read the issue first and note the expected behavior and any maintainer guidance.
2. Read the reproduction evidence and note the reproduced failure.
3. Read the plan and identify its diagnosis, scope, files, approach, and test plan.
4. Read the proposed plan comment last and compare it with the plan and issue thread.

## Evidence gathering

1. **Diagnosis:** Compare the reproduction evidence with the plan diagnosis. Record at least one stated root cause.
2. **Scope:** Read the plan scope section. Record at least one in-scope or not-in-scope boundary.
3. **Files:** Read the plan files section. Record at least one specific file path that will be changed.
4. **Approach:** Read the plan approach. Record at least one specific implementation step that addresses the root cause.
5. **Test plan:** Compare the plan test section with the reproduction. Record at least one test or command and its expected result.
6. **Plan Comment:** Read the GitHub issue thread and proposed plan comment. Record at least one relevant maintainer comment and check that the proposed comment follows that guidance and does not promise work outside the plan.

## Check execution

Grade the checks in this order:

1. Diagnosis
2. Scope
3. Files
4. Approach
5. Test plan
6. Plan Comment

For each check:

- Mark `pass` if its pass condition is clearly supported by the gathered evidence.
- Mark `fail` if the pass condition is not met.
- If the required evidence is missing or unclear, mark it `fail`.
- Use the evidence already gathered instead of assuming missing information.

## Verdict assembly

1. Review all Required checks.
2. If every Required check passes, return `accept`.
3. If any Required check fails, return `reject`.
4. Unclear evidence counts as a failure.
5. In the output, quote the plan or reproduction evidence that supports each grade.
6. For a rejection, clearly identify the Required check or checks that caused the rejection.