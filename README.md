# writing-whip

A Claude skill that removes AI writing tropes at the point of generation. It lists response behaviours (reasoning leaks, preambles, tie-back endings) and writing patterns (negative parallelism, em-dash overuse, magic adverbs) for Claude to avoid.

Original skill by Ossama Chaib: https://gist.github.com/ossa-ma/dae6f9571534f3fbd1266a384be00e11

The only change here is the frontmatter `name`, set to `writing-whip` so it registers as `/writing-whip`.

## Install

```bash
mkdir -p ~/.claude/skills/writing-whip
curl -L https://raw.githubusercontent.com/aj-suresh/writing-whip/main/writing-whip/SKILL.md -o ~/.claude/skills/writing-whip/SKILL.md
```

Restart Claude Code, then run `/writing-whip` or let Claude load it before writing tasks.
