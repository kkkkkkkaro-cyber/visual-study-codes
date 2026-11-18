# Install Visual Study Codes in OpenAI Codex

Visual Study Codes is a portable Agent Skill. The repository's root `SKILL.md` is the skill entry point and is shared with Claude Code; Codex does not need a separate implementation.

## User-level installation

This makes the skill available across your Codex projects:

```bash
git clone https://github.com/kkkkkkkaro-cyber/visual-study-codes ~/.codex/skills/visual-study-codes
```

## Project-level installation

Run from the root of the project where you want to use the skill:

```bash
mkdir -p .agents/skills
git clone https://github.com/kkkkkkkaro-cyber/visual-study-codes .agents/skills/visual-study-codes
```

## Use

After installation, restart or refresh Codex if the skill is not detected. Invoke it by naming `visual-study-codes` or by entering a supported code and topic, for example:

- `/roadmap coffee from bean to cup`
- `/flowchart how photosynthesis works`
- `/sketchnotes` followed by notes or source text
- `/weekly-plan` followed by your own schedule

The skill contains 16 codes. See the repository [README](../README.md) for the full list and visual examples.

For current Codex skill discovery behavior, see the [official Codex Skills documentation](https://developers.openai.com/codex/skills/).
