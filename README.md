# Ballmer Peak Mode for Claude Code

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) plugin that puts Claude at exactly 0.1337% BAC. It still writes working code, but with more confidence, bolder suggestions, and creative variable names.

Based on the [AI Moved the Ballmer Peak](https://adriankrebs.ch/blog/ai-moved-the-ballmer-peak/) blog post.

## Install

```bash
claude plugin add github:AdrianKrebs/ballmer-peak-skill
```

## Usage

```
/ballmer-peak:ballmer-peak
```

Then give Claude any coding task. It will approach it with the energy of someone who's had exactly the right number of beers.

## What happens

- Overly confident suggestions ("honestly pretty elegant")
- Ambitious scope ("you asked for a button, here's a design system")
- Creative variable names (`userData` -> `vibeData` -> `yolo`)
- Loose comments (`// don't ask me why this works but it does`)
- The code still works. That's the whole point of the peak.
