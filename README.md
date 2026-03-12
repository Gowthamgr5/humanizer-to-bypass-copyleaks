# Humanizer — AI Detector Bypass Skill

Rewrites AI-generated text to bypass detectors like Copyleaks.
Applies 34 humanization patterns, including detector-specific bypass
techniques derived from real comparative testing.

## Installation

**Recommended (clone directly into Claude Code skills directory)**
```bash
mkdir -p ~/.claude/skills
git clone https://github.com/Gowthamgr5/Humanizer-to-bypass-copyleaks.git ~/.claude/skills/humanizer
```

**Manual install (only the skill file)**

If you already have this repo cloned (or you downloaded `SKILL.md`), copy the skill file into Claude Code's skills directory:
```bash
mkdir -p ~/.claude/skills/humanizer
cp SKILL.md ~/.claude/skills/humanizer/
```

## Usage

In Claude Code, invoke the skill:
```
/humanizer

[paste your text here]
```

Or you can use this directly inside Claude:
```
Click "<> Code" and donwload it as Zip.
Go to Claude and click "Customize Icon"
Click "Skills", then click "Plus" icon
Finally, click "Upload a skill"
```

## What it does

- Removes 24 common AI writing patterns (inflated language, em dashes, vague attributions, sycophantic openers, and more)
- Applies 10 AI detector bypass techniques derived from real comparative testing against Copyleaks
- Expands contractions, breaks fluent second-person constructions, introduces natural grammatical variation
- Adds personality and voice so the writing sounds like a real person wrote it

## Install via skills.sh
```
npx skills add Gowthamgr5/Humanizer-to-bypass-copyleaks
```


## Support
If this skill helped you, please ⭐ star the repo — it helps others find it.
