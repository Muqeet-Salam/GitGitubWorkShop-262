# Challenge 05: Rebase Time Machine (Medium)

## Objective
Clean up commit history using interactive rebase.

## Files
- `timeline.md`

## Task
1. Create branch `history-cleanup`.
2. Make 3 small commits in `timeline.md` with rough messages:
   - `wip1`
   - `wip2`
   - `wip3`
3. Use interactive rebase to squash these into ONE clean commit:
   - `challenge-05: added final project timeline`
4. Merge `history-cleanup` into `main`.

## Hint
Use `git log --oneline -n 5` before and after rebase.

## Success Criteria
- WIP commits no longer appear separately.
- One clean commit remains.
