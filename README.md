# Cybersecurity Supercommunicator Coach

An AI agent skill that coaches cybersecurity professionals to design and deliver outstanding presentations. Based on the blog series *"Cybersecurity Needs Supercommunicators"* and *"Become a Cybersecurity Supercommunicator"* by Federico Maggi.

## Why This Exists

Cybersecurity is a public-interest good. Poor communication in this field means delayed patching, misplaced priorities, public misinformation, and slow talent growth. Strong research deserves strong delivery, yet many technically brilliant speakers fall into the **credibility-impact gap**: the audience assumes delivery quality reflects research quality.

This skill transforms AI agents into expert presentation coaches that help speakers close that gap.

## What It Does

- **Message Design**: Craft a crisp, memorable 280-character core takeaway
- **Audience Targeting**: Optimize for specific audience segments (peers, executives, press, academia)
- **Story Architecture**: Build narrative arcs with tension and resolution instead of flat slide decks
- **Visual Strategy**: Design visuals that support the narrative, not dominate it
- **Delivery Coaching**: Improve body language, voice modulation, and stage presence
- **Preparation Planning**: Follow a timeline-based process with quality gates
- **Venue Adaptation**: Adjust approach for academic vs. practitioner conferences
- **Speaker Style Assessment**: Identify your archetype (Analyst, Visionary, Educator, Inspirer) and leverage its strengths

## Usage with Claude Code

### Install as a Skill

Copy or symlink `SKILL.md` into your Claude Code project directory or your global `~/.claude/` config:

```bash
# Option A: Clone into your project
git clone https://github.com/<owner>/cybersecurity-speaker-coach.git
cd cybersecurity-speaker-coach

# Option B: Symlink into your global Claude config
ln -s /path/to/cybersecurity-speaker-coach/SKILL.md ~/.claude/commands/cybersecurity-speaker-coach.md
```

### Start a Coaching Session

Once the skill is loaded, ask Claude Code to coach you:

```
I have a 30-minute talk at Black Hat in 6 weeks about a firmware vulnerability
we found in industrial control systems. Can you help me prepare?
```

Claude will walk you through the methodology:

1. Identify your target audience
2. Write your core message (280 chars)
3. Decompose into 3-4 sub-messages
4. Design narrative arcs
5. Build speaker notes before slides
6. Review visuals, code, and diagrams
7. Coach delivery technique
8. Manage preparation timeline and logistics

### Example Prompts

```
Help me write a core message for my DEF CON talk on cloud misconfiguration research.
```

```
Review my speaker notes and help me cut content that doesn't serve the core message.
```

```
I have this code block I want to show on stage. Help me reduce it to the essential lines.
```

```
What speaker archetype am I? Ask me the assessment questions.
```

```
My talk is in 2 weeks. Give me a preparation checklist.
```

## Methodology Overview

The skill follows a phased approach:

| Phase | Timing | Focus |
|-------|--------|-------|
| **Foundation** | 4-6 weeks out | Audience, core message, sub-messages |
| **Story Architecture** | 3-4 weeks out | Narrative arcs, content selection, speaker notes |
| **Visual Design** | 2-3 weeks out | Slides, code reduction, diagram reveals |
| **Delivery Mastery** | 1-2 weeks out | Body language, voice, rehearsals |
| **Logistics** | Final days | Venue prep, tech checks, anxiety management |

Core philosophy: **Start from the last slide.** Design your takeaway message first, then build everything backward from there.

## Anti-Patterns the Coach Will Flag

- Starting with PowerPoint instead of story design
- Filler openings ("I'm honored to be here...")
- Agenda slides that spoil the narrative
- Walls of code or text
- Ego-driven "whoami" introductions
- Explaining the bug before explaining the impact
- Confusing comprehensive coverage with impact

## Who This Is For

- Security researchers presenting at conferences (Black Hat, DEF CON, RSA, IEEE S&P, USENIX)
- Technical professionals communicating findings to non-technical stakeholders
- Cybersecurity educators and trainers
- Product security teams presenting vulnerabilities or mitigations
- Academic researchers preparing conference papers and talks
- Anyone translating deep technical work into accessible presentations

## References

- Maggi, F. (2025). *"Cybersecurity Needs Supercommunicators."*
- Maggi, F. (2026). *"Become a Cybersecurity Supercommunicator."* Includes downloadable slide deck: https://supercommunicators.trustial.org
- Duhigg, C. (2024). *Supercommunicators*. Random House.
- Reynolds, G. (2019). *Presentation Zen*. New Riders.
- Duarte, N. (2010). *Resonate*. Wiley.

## License

See [LICENSE](LICENSE) for details.
