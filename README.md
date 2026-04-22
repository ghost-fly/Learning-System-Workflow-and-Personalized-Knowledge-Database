# Learning-System-Workflow-and-Personalized-Knowledge-Database
Putting this out there and looking for any input/feedback from greater outreach. It is an attempt to build a mental framework and robust workflow process for learning and Personalized Knowledge Database. It leverages AI technology but leaves the judgement call to the human owner.
## INTRODUCTION
Most personal knowledge systems fail at one of two things: either they're great at capturing information but terrible at processing it into something you actually understand and retain, or they outsource the thinking to AI and leave you with a polished database you never truly absorbed.
Steph Ango's Obsidian workflow excels at capture and connection but lacks a rigorous processing protocol — notes accumulate without systematic refinement. Andrej Karpathy's LLM Wiki solves the maintenance problem by having the LLM write and cross-reference everything, but the LLM controls what gets extracted, emphasized, and synthesized — the human reviews the output but never makes the upstream filtering decisions. Your knowledge base ends up reflecting the LLM's judgment about what matters, not yours.
This system attempts to bridge that gap: a staged pipeline where information is captured, distilled, adversarially tested, tagged, archived, and periodically reviewed — with AI handling the grunt work (indexing, suggesting connections, generating review prompts) while the human retains the intellectual labor that produces real learning.
Looking for feedback and critique, especially from anyone who's actually sustained a PKM system beyond the first few months.

On one reflection, it seems like an architecture on which a software/app could be built on.

This work does not claim any invention or discovery. It is more of an attempt at distillation and systematization. 

## TOOLS USED
- **File format:** Markdown
- **Interface:** Obsidian
- **Intellectual Engine:** Human owner + LLM of choice
- **To work with system:** IDE of choice + LLL of choice

## DESCRIPTION OF THE WORK
A personal knowledge vault built around a four-stage pipeline: Capture → Reference → First Form → Shelf. Every idea enters as a rough capture and earns its way onto the shelf through an explicit promotion gate — a seven-question protocol designed to catch rented understanding before it compounds.
Five LLM roles are wired as slash commands, each with a narrow posture and invoked one at a time:
•	Tutor — explains a concept when you're stuck
•	Socratic Interlocutor — exposes what you actually know versus assume
•	Devil's Advocate — tries to break a note before it's promoted
•	Librarian — handles cross-links, tags, and index bookkeeping
•	Lint Auditor — runs a monthly health check on the vault
The design principle is a deliberate division of labor: the human evaluates sources, decides what is true, and writes the note content. The LLM maintains structure, runs scrutiny on request, and handles all housekeeping. The LLM never decides what survives.

Everything lives in plain markdown with YAML frontmatter and wikilinks, so the vault is portable forever and works in vanilla Obsidian without plugins. Notes are atomic where they can be, map-shaped where they can't, with granularity discovered through decomposition rather than decreed up front.

Comes with templates for each stage, weekly/monthly review routines, and a CLAUDE.md operating contract an LLM reads at session start.

---

![](LSW%20%26%20PKD%20System%20At%20Glance%20Diagram.png)

---

