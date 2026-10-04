# Executive Communication & Strategic Thinking Skill

Turn operational updates into clear recommendations, ask better strategic questions, and connect your work to business priorities with SCAR.

Use it to:

- Rewrite operational updates as recommendations that help leaders make decisions.
- Prepare questions about outcomes, priorities, and tradeoffs.
- Explain how an achievement contributes to a leadership priority.
- Turn data into an insight and a supported next step.
- Review communication examples and feedback about strategic positioning.

The skill distinguishes facts, targets, forecasts, and assumptions. It keeps technical detail when the audience needs it and tests objections against evidence.

## Install in Claude Code

Download this repository with **Code → Download ZIP** and extract it.

Copy the `executive-strategic-positioning` folder into your personal skills directory:

```text
~/.claude/skills/executive-strategic-positioning/SKILL.md
```

To make the skill available only within one project, copy that folder into the project's `.claude/skills/` directory instead.

In Claude Code, invoke it with:

```text
/executive-strategic-positioning
```

See the [Claude Code skills documentation](https://code.claude.com/docs/en/skills) for installation locations and invocation details.

## Update an existing installation

If you already installed this repository as `executive-communication`, update the whole repository so that the root `SKILL.md` can load the current instructions from `executive-strategic-positioning/SKILL.md`.

The existing `/executive-communication` command remains available. New installations can use the standalone `executive-strategic-positioning` folder and command described above.

The repository remains at [demianvalenzuela/executive-communication](https://github.com/demianvalenzuela/executive-communication).

## Download the packaged skill

[Download executive-strategic-positioning.skill](executive-strategic-positioning.skill?raw=true).

The `.skill` file is a ZIP archive containing the skill folder, its `SKILL.md`, and the MIT license. For an agent that accepts skill archives, follow that agent's import instructions. If the importer requires a `.zip` extension, rename the downloaded file before importing it.

The editable instructions are in [executive-strategic-positioning/SKILL.md](executive-strategic-positioning/SKILL.md).

## Try it

Start with one of these requests, then provide your content and context:

> Rewrite this update for our VP of Sales. The decision is whether to fund a retention pilot. Apply SCAR, preserve the supplied numbers, and flag claims that need evidence.

> Prepare four questions for a leadership meeting about entering a new market. Focus on outcomes, priorities, and tradeoffs.

> Help me explain how reducing a process from 10 hours a week to 2 supports our capacity goals. Do not assume the saved time has already generated revenue.

> Turn these churn figures into an executive insight. Separate what the data shows from hypotheses and recommend the next analysis or action.

For a stronger result, include the audience, the decision you want to inform, current priorities, supporting data, and known constraints.

The instructions are in English. Ask for the output in the language your audience uses.

## License

This skill and its documentation are available under the [MIT License](LICENSE).

Copyright (c) 2026 Demian Valenzuela.
