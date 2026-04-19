# Challenge 07: Cherry-Pick Heist (Hard)

## Objective
Move one useful commit from one branch to another using cherry-pick.

## Files
- `feature-a.txt`
- `feature-b.txt`

## Task
1. Create branch `experiment-a`.
2. Add one useful line to `feature-a.txt` and commit:
   - `challenge-07: add reusable fix in experiment-a`
3. Add one unrelated line to `feature-a.txt` and commit:
   - `noise commit`
4. Switch to `main`.
5. Cherry-pick ONLY the useful fix commit from `experiment-a`.
6. Confirm `noise commit` changes are not in `main`.

## Success Criteria
- Exactly one commit is cherry-picked.
- `main` has only the useful change.
