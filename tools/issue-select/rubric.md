# Rubric: is this a good first issue?

<!--
THIS IS THE PART YOU WRITE. The skill in SKILL.md executes whatever checks
you define here. It ships empty on purpose: the judgment is your work.

A filled rubric must contain:

1. At least one row in the checks table. Each row needs all four columns:
   - Check: a short name (used in the output JSON).
   - Evidence: exactly what to look at, and where. Name the source
     (repo-facts block, issue body, comment thread, or the locations in
     references/evidence-guide.md). "The repo" is not a source; "the last
     5 default-branch commit dates" is.
   - Pass condition: a condition someone else could apply and get your
     answer. Prefer thresholds with numbers ("a maintainer commented
     within 30 days") over adjectives ("maintainer is responsive").
   - Weight: `required` (a fail here rejects the issue) or `preferred`
     (never changes the verdict; a nice-to-have that helps rank the
     issues you accept).

2. A verdict rule below the table: how the check grades combine into
   accept or reject, including how `unclear` is treated. The verdict
   space is binary. If you write no rule for `unclear`, the skill treats
   it as fail.

Cover what actually kills first contributions. The lecture named four
families: the maintainer is alive, the repo is in use, the scope fits a
newcomer, and nobody else is already on it. A rubric that ignores a family
will fail eval issues designed around that family.
-->

## Checks

| Check | Evidence | Pass condition | Weight |
|---|---|---|---|
| Is the maintainer still active? | Check repository's recent commit or push activity | Last repository activity within 30 days | Required |
| Is the maintainer responding to contributors? | Check recent issue/PR activity for maintainer responses | Pass if at least 1 maintainer response occurred within 90 days | Required |
| Is the issue unclaimed? | Check assignee, linked PRs, and status | Pass only if no assignee, no active linked PR, and not `in progress` | Required |
| Does the issue have repeated abandoned attempts? | Check issue comments and PR history | Fail if multiple contributors previously attempted and abandoned the issue | Required |
| Does the repo allow AI-assisted contributions? | Check CONTRIBUTING.md and AI policy | No explicit ban on AI-generated contributions; conditions and silence pass | Required |
| Is it beginner friendly? | Check labels and CONTRIBUTING.md | Has `good first issue`, `help wanted`, or a clearly small/easy task | Preferred |

## Verdict rule
- Accept only if ALL Required checks pass.
- Reject if ANY Required check fails.
- Preferred checks do not affect the verdict, they
rank accepted issues
- If unclear then count as fail
<!-- State how the grades above combine into accept or reject, and how
unclear is treated. Example shape (write your own): "accept if every
required check passes; preferred checks never change the verdict, they
rank accepted issues; unclear counts as fail." -->
