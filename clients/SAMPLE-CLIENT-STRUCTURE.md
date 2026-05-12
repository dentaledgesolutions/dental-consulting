# Sample Client Folder Structure

Use this structure for each client project:

```
clients/[client-name]/
├── background.md          # Client info, market, goals
├── goals.md              # What we're analyzing & why
├── notes.md              # Your observations & findings
└── deliverables/         # Final work for client
    ├── pain-points-analysis.md
    ├── competitor-benchmarking.md
    ├── service-recommendations.md
    └── presentation.md
```

## Example: Bright Smile Dental (Miami)

```
clients/bright-smile-dental/
├── background.md
│   - Practice: 3 dentists, 2 hygienists, Miami location
│   - Revenue: ~$800K annually
│   - Goal: Improve patient acquisition, reduce no-shows
│   
├── goals.md
│   - Need: Pain point analysis + service recommendations
│   - Focus: New patient acquisition (CAC too high)
│   - Timeframe: 2 weeks for initial analysis
│   
├── notes.md
│   - Initial call: Owner concerned about DSO competition
│   - Current tech: Old Dentrix system, manual scheduling
│   - Staff: Turnover issues, especially hygiene
│   
└── deliverables/
    ├── pain-points-analysis.md
    ├── competitor-benchmarking.md
    └── service-recommendations.md
```

## Files to Include in Each Client Folder

### background.md
- Client name, location, website
- Practice size (# dentists, hygienists, staff)
- Current revenue/patient count (if available)
- Current technology/systems
- Current pain points (per client)
- Market context

### goals.md
- What analysis they need
- Which decision-maker we're presenting to
- Success criteria
- Timeline

### notes.md
- Key quotes from conversations
- Observations
- Competitive landscape notes
- Assumptions to validate
- Follow-up questions

### deliverables/
- Save analyses here
- Use consistent naming: [type]-[date].md
- Example: pain-points-analysis-2025-05.md

## How to Use

```bash
# Create new client
mkdir clients/[client-name]

# Copy template files (optional)
cp templates/analysis-template.md clients/[client-name]/analysis.md

# Create deliverables subfolder
mkdir clients/[client-name]/deliverables

# Run analysis with client context
claude -p "Analyze pain points for the following practice:" < clients/[client-name]/background.md

# Save output
# Claude will save to ~/projects/dental-consulting/outputs/
# Then move to clients/[client-name]/deliverables/
```
