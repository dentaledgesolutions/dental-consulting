# Dental Consulting Project

Professional dental business consulting using Claude's dental-edge-consultant skill.

## Quick Start

```bash
cd ~/projects/dental-consulting
claude -p "Analyze pain points for a dental practice in [region]"
```

## Folder Structure

- **clients/** — Client info, contacts, background research
- **analyses/** — Completed analyses (pain points, competitors, services)
- **templates/** — Reusable analysis templates
- **notes/** — Research notes, findings, observations
- **research/** — Market data, competitor research, industry insights
- **resources/** — Reference guides (GoHighLevel, competitors list, examples)
- **outputs/** — Final deliverables, reports, presentations

## Using the Skill

The dental-edge-consultant skill is installed and ready to use. It supports:

- **Pain points only:** `"Analyze top 5 pain points for [region] practices"`
- **Competitor analysis:** `"Compare Weave vs. RevenueWell for dental practices"`
- **Service recommendations:** `"What services should we offer dental practices?"`
- **Full analysis:** `"Run comprehensive analysis for [client/region]"`

## Analysis Workflow

1. **Brief the skill:** "I need analysis for [client/region]. Here's context: [background]"
2. **Request specific output:** "Pain points only" or "Full 9-section report"
3. **Save results:** Claude will save to outputs/ folder
4. **Refine:** Ask follow-up questions or request specific sections

## Resources Available

- **GoHighLevel Capabilities Guide** — What GoHighLevel can/can't do
- **Competitor Reference List** — 9+ key competitors in dental tech
- **Example Outputs** — Real completed analyses you can use as templates
- **Pain Point Framework** — Standard pain points by role

See `resources/` folder for all reference materials.
