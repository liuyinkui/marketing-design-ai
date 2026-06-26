# marketing-design-ai

An AI-assisted marketing design playbook for turning campaign briefs into strategy, copy, visual direction, review notes, and delivery packages.

This repository is documentation-first. It is meant to be read by humans and by AI agents that help with marketing design work.

## What This Repository Is For

- Standardizing how marketing design work starts, develops, gets reviewed, and ships.
- Giving AI agents clear instructions for common tasks such as banners, landing pages, campaign pages, AI image direction, and copywriting.
- Keeping prompts, templates, examples, and quality standards in one reusable place.

## Recommended Operating Flow

1. Start with `workflows/01_brief.md` and capture the project inputs in `templates/creative-brief.md`.
2. Use `workflows/02_strategy.md` to define the audience, offer, message hierarchy, and channel plan.
3. Use the relevant skill file in `skills/` to create the deliverable.
4. Use `workflows/04_review.md` and `docs/quality-standards.md` before delivery.
5. Package final notes with `templates/delivery-report.md`.

## Repository Layout

- `skills/` - task playbooks for specific marketing design capabilities
- `workflows/` - the standard end-to-end process from brief to delivery
- `prompts/` - reusable prompts for AI-assisted execution
- `templates/` - fill-in templates for briefs, plans, specs, and reports
- `examples/` - complete sample projects that show the system in use
- `docs/` - quality standards and supporting guidance
- `assets/` - source files, references, exported visuals, and supporting materials

## Who Should Use This

- Designers who want a consistent AI-assisted design process.
- Marketers who need clearer briefs, campaign logic, and review criteria.
- AI agents that need structured context before producing design or copy outputs.

## Contribution Notes

- Keep documents practical and executable.
- Add examples when a rule may be interpreted in more than one way.
- Update the nearest `README.md` when adding a new file category.
- Prefer specific output formats over broad advice.
