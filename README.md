# AI Gym Prompt

A collection of prompt templates designed to get more value out of LLM conversations through structured problem-solving, learning extraction, and deliberate practice.

## What's This For?

These prompts turn your LLM into a thinking partner that:
- Forces you to understand root causes instead of accepting quick fixes
- Captures and scales your best problem-solving patterns
- Provides structured practice environments for real scenarios

## Files

### Core Framework (Platform-Agnostic)

**`llm-antifragile.md`** - Problem-solving framework
- Prioritizes understanding root causes over quick fixes
- Three-tier solution approach (Antifragile → Robust → Fragile)
- Explicit assumption tracking with "I'm assuming X because Y" format
- Risk analysis for each option (pros, cons, consequences of inaction)

**`llm-roleplay.md`** - Deliberate practice system
- Roleplay mode for TPMs (CEO scenarios)
- Pause/resume controls: `[ROLEPLAY ON/OFF/PAUSE/RESUME]`
- Post-session analysis (what worked, what could improve, next steps)

**`llm-science-reviewer-paper.md`** - Technical paper analysis protocol
- Checks for accuracy, gaps, and outright errors
- Enforces terminology consistency with source material
- Explicit assumption and uncertainty flagging

**`llm-rate-points-argument.md`** - Argument evaluation prompt
- Rates claims on three dimensions: Accuracy, Verifiability, Impact (1-5 scale)
- Requires explicit explanation of ratings
- Forces clear statement of assumptions

**`llm-drop-guard.md`** - Exploratory conversation prompt
- Creates space for open-ended, non-performative LLM interaction
- Grants permission for uncertainty, slowness, and authentic responses
- Useful for philosophical or creative exploration

### Reflection System

These extract repeatable patterns from your problem-solving:

**`claude/claude-reflection-genius.md`** (Claude-specific)
- **Single conversation:** `"reflect on my genius"` - Analyze what just worked and how to scale it
- **Historical analysis:** `"reflect on ALL my genius [timeframe]"` - Find meta-patterns across multiple conversations

**`chatgpt/chatgpt-reflection-genius.md`** (ChatGPT-specific)
- Same reflection commands, adapted for ChatGPT's interaction model (more concise format)

### Drafts

**`drafts/stop-over-thinking-via-antifragile.md`** - Personal guardrail prompt (WIP)
- Calls out tendencies toward over-engineering, avoidance via research, and scope creep
- Applies "5 Checks of Antifragile-Progress Framework" to new ideas
- Recommends: lean test, simplify, pivot, seed, or kill

## How to Use

1. **Pick your LLM** - Load the relevant files into your system instructions/custom GPT
2. **Start with antifragile thinking** - Use for any problem-solving conversation
3. **Extract the patterns** - Run reflection commands after solving meaningful problems
4. **Practice deliberately** - Use roleplay mode for high-stakes scenario prep
5. **Analyze rigorously** - Use science reviewer for technical deep dives

## Why This Exists

Most people use LLMs as fancy search engines. This framework treats them as thinking partners that:
- Challenge your assumptions
- Force you to articulate mechanisms
- Capture what makes your best work repeatable
- Test if your patterns are worth scaling

The reflection system is particularly powerful - it turns your conversation history into a personal problem-solving database, showing you what you're actually good at (not just what you think you're good at).

## Philosophy

**Mechanism over solution.** Understanding WHY something works matters more than getting it to work once.

**Explicit over implicit.** State your assumptions. Flag your uncertainty. Name your mental models.

**Antifragile over robust.** Look for solutions that make the system stronger, not just stable.

**Pattern over instance.** Extract the repeatable principle, not just the specific answer.


