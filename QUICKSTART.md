# Quickstart Guide

## 1. Navigate to Project
```bash
cd ~/projects/dental-consulting
```

## 2. Run Analysis
```bash
# Pain points for a region
claude -p "Analyze the top 5 pain points for independent dental practices in South Florida"

# Competitor analysis
claude -p "Compare RevenueWell, Weave, and CareStack for dental practices"

# Full analysis
claude -p "Run a comprehensive analysis for a dental marketing agency entering the Miami market"
```

## 3. Save Results
```bash
# Claude automatically saves outputs to ~/projects/dental-consulting/outputs/
# Name your file:
# outputs/client-name-pain-points.md
# outputs/client-name-full-analysis.md
# outputs/competitor-benchmarking.md
```

## 4. Organize Client Work
```bash
# Create client folder
mkdir clients/[client-name]
cd clients/[client-name]

# Files to add
- background.md (client context)
- goals.md (what they want analyzed)
- notes.md (your observations)
```

## 5. Use Templates
Copy from `templates/` folder when creating new analyses. Templates match skill output format.

## Reference Materials
- `resources/gohighlevel-capabilities.md` — GoHighLevel feasibility
- `resources/dental-competitors.json` — Competitor data
- `resources/skill-examples.md` — Example outputs

## Claude Code Commands

**Start interactive session:**
```bash
claude
```

**Run single analysis:**
```bash
claude -p "Your analysis request"
```

**With file context:**
```bash
claude -p "Analyze this practice context" < clients/client-name/background.md
```

## Tips

- Be specific about region (Miami, South Florida, national, etc.)
- Include client context when available
- Ask for "pain points only" if you want quick analysis
- Use full 9-section report for comprehensive work
- Reference competitors by name for better benchmarking

## Skill Features

✅ Flexible request modes (partial or full)
✅ Regional market context included
✅ GoHighLevel feasibility assessment
✅ Competitor benchmarking
✅ Revenue impact quantification
✅ Pitch templates for decision-makers

See README.md for more details.
