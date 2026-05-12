# Test Analysis Instructions

Run this command to verify the setup works:

```bash
cd ~/projects/dental-consulting
claude -p "Analyze the top 5 pain points for independent dental practices in South Florida. Keep it focused (pain points only, no full report)."
```

## Expected Output

You should get back:
- 5 pain points identified
- Roles affected (Owner/Manager/Dentist)
- Business impact with specifics ($, %, hours)
- Urgency levels (High/Medium/Low)
- South Florida market context

## Save Results

Claude will auto-save to outputs/ folder. Then:

```bash
cp outputs/[filename] clients/[client-name]/deliverables/
```

## Verification Checklist

- [ ] Command runs without errors
- [ ] Output appears in outputs/ folder
- [ ] Pain points are specific (not generic)
- [ ] Includes dollar amounts and percentages
- [ ] South Florida context is included
- [ ] Can move output to client folder

If all pass ✅ → **Setup is working perfectly!**

---

**Status:** Ready to use. Start with this test, then create real client analyses.
