# notes/

Personal study notes for the System Design Primer. Kept in a fork so it stays synced with upstream ([donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer)).

- **`study-tracker.md`** — progress checklist across all topics + a plan by timeline. Start here.
- **`_topic-template.md`** — copy this per topic (e.g. `cap-theorem.md`) to take structured notes.

## Workflow
```bash
# save notes
git add notes/ && git commit -m "notes: <topic>" && git push   # -> your fork (origin)

# pull upstream updates without losing your notes
git fetch upstream && git merge upstream/master
```
Your notes live only under `notes/`, so upstream merges never conflict with them.
