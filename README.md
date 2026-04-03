# claude-skills

A collection of shareable [Claude Code skills](https://docs.anthropic.com/en/docs/claude-code/skills) -- reusable prompt-based capabilities that extend what Claude can do in a conversation.

## What are Claude Skills?

Claude Skills are markdown files (`SKILL.md`) that teach Claude how to perform specific tasks. They act as structured prompts that guide Claude through multi-step workflows, frameworks, or processes. Skills can be installed into any Claude Code project to give Claude new capabilities without writing code.

## Skills

| Skill | Description |
|---|---|
| [uncertainty-navigator](skills/uncertainty-navigator/) | Apply the Rumsfeld Matrix and PREP Framework to navigate decisions, initiatives, or challenges under uncertainty. |

## Installation

Skills can be installed at two levels:

### Project-level (shared with your team via version control)

```bash
# From your project root
mkdir -p .claude/skills
cp -r skills/uncertainty-navigator .claude/skills/
```

### User-level (available across all your projects)

```bash
mkdir -p ~/.claude/skills
cp -r skills/uncertainty-navigator ~/.claude/skills/
```

Once installed, Claude Code automatically discovers the skill -- no restart needed. You can verify by typing `/` in Claude Code to see available skills, or run `/skills` to list them.

### Usage

Skills with a `name` in their frontmatter can be invoked directly:

```
/uncertainty-navigator
```

Or just describe what you need and Claude will activate the skill automatically when it's relevant to your request.

## Contributing

To add a skill:

1. Create a new folder under `skills/` with your skill name
2. Add a `SKILL.md` file following the standard skill format (frontmatter with `name` and `description`, then the skill instructions)
3. Open a PR
