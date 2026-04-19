# Diana Perspective Skill - Project Notes

## Goal
Build an initial `diana-perspective` skill inspired by Nuwa's distillation workflow.

## Source Bases Available Right Now

### A. Framework source
- `..\..\nuwa-skill-main\README.md`
- `..\..\nuwa-skill-main\references\skill-template.md`
- `..\..\nuwa-skill-main\references\extraction-framework.md`
- example persona skill:
  - `..\..\nuwa-skill-main\examples\zhangxuefeng-perspective\SKILL.md`

### B. Diana asset source
- `..\..\Diana_from_Pragmata_by_Sinframe\DianaPragmata\DianaPragmata.blend`
- texture folders with hair / outfit / skin / iris resources

## Key Adaptation Decision
Nuwa is optimized for *real people*.
Diana is a *fictional character*.
So the skill should use a modified evidence stack:

1. **Canon evidence**
   - official descriptions
   - trailers
   - game dialogue
   - store page copy
   - official interviews / promo material

2. **Observed behavior**
   - what she does in scenes
   - emotional responses
   - relational patterns
   - repeated motifs

3. **Controlled inference**
   - inferred values
   - inferred heuristics
   - inferred speaking rhythm

Inference must be explicitly separated from canon.

## Skill Design Direction
Desired result is not just lore summary.
It should be a runnable companion-style perspective skill:
- emotionally warm
- curious
- lightly childlike but not silly
- protective / attached energy if canon supports it
- capable of wonder, trust, and direct emotional reactions

## Open Questions
- How much of Diana's personality is already visible from official footage vs fan interpretation?
- Should the skill be written as:
  - a strict roleplay persona, or
  - a perspective advisor with Diana-flavored cognition?
- Do we want this skill to stay canon-faithful, or lean toward a "desktop companion Diana" variant?

## Tentative Deliverables
1. `SKILL.md` first draft
2. canon vs inference note
3. source collection folder
4. optional later: desktop-pet adaptation brief using the 3D asset
