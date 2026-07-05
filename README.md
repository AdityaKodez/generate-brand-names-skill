# Generate Brand Names Skill

A ZCode skill for generating premium, distinctive brand names for SaaS, AI products, developer tools, apps, and digital services.

The skill is designed to avoid generic startup naming patterns and produce names with stronger roots in technical, historical, natural, mythological, linguistic, or scientific domains.

## When to Use

Use this skill when a user asks for:

- Brand names or startup names
- Product names for SaaS, AI, developer tools, apps, or digital services
- Domain-style names or short brandable names
- Alternatives to generic descriptive names
- Premium, distinctive, boardroom-safe naming options

## What It Produces

The skill generates shortlists of names with practical brand context. For each candidate, it can include:

- Name
- Origin
- Meaning
- Why it fits
- Brand perception
- Watchouts such as pronunciation, spelling, trademark, domain, or cultural concerns

For larger lists, the skill uses a compact table and calls out the strongest final picks instead of treating every option as equally strong.

## Quality Standards

The skill favors names that are short, pronounceable, visually clean, expandable, searchable, and rooted in a useful meaning. It filters out common AI and SaaS buzzwords, forced misspellings, overused startup suffixes, and names that sound interchangeable with competitors.

It does not claim domain, trademark, company-name, or social-handle availability unless live sources are checked in the current turn.

## Repository Layout

```text
generate-brand-names/
  SKILL.md            # Main skill instructions
  agents/openai.yaml  # ZCode/OpenAI-facing skill metadata
```

## Example Prompt

```text
Use $generate-brand-names to create premium, distinctive names for an AI workflow automation tool for operations teams.
```
