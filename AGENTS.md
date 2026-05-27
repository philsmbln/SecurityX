# AI Agent Instructions for SecurityX

## What this repository is

SecurityX is a structured cybersecurity knowledge base composed entirely of Markdown documents. It is organized by major cybersecurity domains:

- `Governance-Risk-Compliance`
- `Security-Architechture`
- `Security-Engineering`
- `Security-Operations`

There is no build system, source code, or automated tests in this repository. Most work is content creation, editing, and documentation organization.

## Agent guidance

- Treat this repository as a documentation-focused knowledge base, not a software project.
- Do not create new executable code files unless the user explicitly asks for code or tooling content.
- Preserve the existing file structure and naming conventions, including spelling and numbered prefixes.
- Do not rename directories or files (for example, `Security-Architechture` is intentionally preserved as existing structure) without explicit user permission.
- When adding new material, follow the existing style: clear titles, short paragraphs, bullet lists, and section-based organization.

## Editing expectations

- Update relevant `.md` files in the correct domain folder.
- Keep headings and filenames consistent with the repository’s numbered topic layout.
- Link to `README.md` or specific domain files rather than duplicating high-level repository-level documentation.
- If the user asks for broader structural changes, ask for confirmation before renaming directories or reworking repository organization.

## Helpful references

- `README.md`: repository overview, goals, structure, and contribution guidance.

## When unsure

- Ask the user before making repository-wide changes.
- Ask the user before correcting spelling in existing directory or file names.
- Ask the user before adding any non-markdown content or executable artifacts.
