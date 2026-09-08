# Contributing

## Adding a new skill

1. Create a new top-level folder named after the skill (kebab-case, e.g. `data-analyze`).
2. Add a `SKILL.md` inside it with YAML frontmatter:
   ```yaml
   ---
   name: skill-name
   description: What it does and when to use it.
   ---
   ```
3. Put any supporting scripts, schemas, or assets alongside `SKILL.md` in the same folder.
4. If the skill has license terms different from the repo's MIT license, include a `LICENSE.txt` in that folder and note it in `SKILL.md`'s frontmatter (see `xlsx/` for an example).
5. Add a row for the skill in the table in [`README.md`](README.md).

## Editing an existing skill

- Keep changes scoped to that skill's folder.
- Update the `description` in `SKILL.md` if the skill's triggering behavior changes.
- Update the corresponding row in `README.md` if the skill's purpose changes.

## Commit messages

Keep them short and describe the change, e.g. `Add data-analyze skill` or `Fix xlsx recalc script`.

## Pull requests

Open a PR against `main`. Describe what the skill does and when it should trigger.
