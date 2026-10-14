

## Checks

| Check | Evidence | Pass condition | Weight |
|---|---|---|---|
| Diagnosis | Reproduction + plan diagnosis → check that the stated root cause explains the reproduced behavior | At least 1 clear root cause | Required |
| Scope | Plan scope section → check what is included and explicitly excluded | At least 1 in-scope or 1 not-in-scope boundary  | Required |
| Files | Plan files section / repository → check exact file paths that need modification | at least 1 specific file | Required |
| Approach |check concrete changes that will fix the root cause  | at least 1 specific implementation step | Required |
| Test plan | Plan test section + reproduction → check exact command/test and expected result after the fix | at least 1 decisive test + 1 expected result | Required
| Plan Comment | GitHub issue thread + proposed plan comment -> check relevant maintainer guidance is addressed and the comment promises only what the plan contains | Follows all relevant maintainer guidance if any exists, and promises only what is in the plan | Required |
 

## Verdict rule

- Accept only if ALL Required checks pass.
- Reject if ANY Required check fails.
- Preferred checks do not affect the verdict, they
rank accepted issues
- If unclear then count as fail