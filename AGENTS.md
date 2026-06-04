# AGENTS

## Repository overview
- This workspace is a minimal static website.
- Primary files:
  - `index.html` — the page content and structure.
  - `style.css` — the site styling.
- There is no build tool, package manager, or test suite in this repository.

## What agents should know
- Keep changes lightweight and aligned with the existing static HTML/CSS structure.
- Do not add frameworks, build tooling, or dependency files unless explicitly requested.
- Preserve the current file structure and name conventions unless a refactor is required.

## Git-focused guidance
- Assume this repository is version-controlled with Git.
- Prefer incremental, well-scoped edits and avoid broad rewrite proposals.
- When suggesting changes, mention the affected files clearly.
- If the user asks for git-related help, focus on practical actions such as:
  - clarifying commit message style,
  - reviewing staged changes,
  - explaining common branch workflows,
  - or helping resolve merge conflicts.

## How to be immediately productive
- Review `index.html` and `style.css` before making frontend or styling changes.
- Use semantic HTML and modern CSS practices appropriate for a simple static page.
- Avoid introducing build steps or dependencies.

## Notes for agents
- There is no documentation beyond the source files.
- If the repo grows later, update this file with new commands or project conventions.
