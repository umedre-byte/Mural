# Quick Start Guide

## Getting Started in 5 Minutes

### Step 1: Install Claude Code

If you haven't already:
```bash
npm install -g @anthropic-ai/claude-code
```

### Step 2: Open This Project

```bash
cd /path/to/mural-lead-agent
claude
```

### Step 3: Update Your Profile

Tell Claude Code:
```
Update my artist profile in config/artist_profile.json with:
- Name: [Your Name]
- Business: [Your Business Name]
- Website: [Your Website]
- Instagram: @[your handle]
- Notable clients: [Client 1, Client 2]
```

---

## Daily Workflow Commands

### Morning: Find New Leads

Copy-paste these into Claude Code:

**Find restaurant leads:**
```
Search for new restaurant openings in Brooklyn from the last 30 days. 
Find ones that look like they'd want murals based on their aesthetic.
For each, find owner name and contact info if possible.
Save results to outputs/leads_restaurants_[today's date].md
```

**Find coffee shop leads:**
```
Search for new coffee shops and cafes that opened in Manhattan recently.
Look for ones with visible wall space in their photos.
Get contact info and save to outputs/leads_cafes.md
```

**Find office leads:**
```
Search for tech companies or creative agencies that recently moved 
to new NYC offices. Look for ones mentioning office design or culture.
Save to outputs/leads_offices.md
```

---

### Afternoon: Research & Draft

**Research a specific business:**
```
Research [BUSINESS NAME] deeply:
- Find the owner or decision maker
- Get their email and phone
- Check their Instagram for interior photos
- Note their design aesthetic
- Find any press mentions
Add this to my leads file.
```

**Draft a pitch email:**
```
Draft a personalized pitch email for [BUSINESS NAME].
They're a [type of business] that just opened in [location].
Use my restaurant template but customize it with:
- [Specific detail you noticed about them]
- Reference my work with [similar past client]
Keep it under 150 words.
```

---

### Weekly: Review & Follow Up

**Weekly summary:**
```
Look at all my leads from this week in the outputs folder.
Summarize:
- How many new leads found
- How many contacted
- Any responses
- What should I prioritize next week
```

**Draft follow-ups:**
```
For any leads I contacted more than 5 days ago with no response,
draft a brief follow-up email.
```

---

## Power User Commands

**Batch lead generation:**
```
Run a full lead generation session for Williamsburg:
1. Search for new restaurants, cafes, and bars
2. Search for new retail stores
3. Search for upcoming brewery openings
4. For the top 10 most promising, get contact info
5. Save everything organized by type to outputs/williamsburg_leads.md
```

**Competitive research:**
```
Search for muralists who recently completed projects in NYC.
What businesses did they work with?
Are there similar businesses nearby that might also want murals?
```

**Public art opportunities:**
```
Search for current public art calls and mural programs in:
- NYC Department of Cultural Affairs
- Brooklyn Arts Council
- NYC parks percent for art
List any open opportunities with deadlines.
```

---

## Tips for Best Results

1. **Be specific with locations** - "Bushwick near the L train" beats "Brooklyn"

2. **Give context** - "They just renovated" helps Claude understand urgency

3. **Reference your style** - "Something that fits my bold, colorful style"

4. **Ask for reasoning** - "Explain why each is a good fit for my work"

5. **Iterate** - "That email is too formal, make it warmer"

---

## Troubleshooting

**Not finding good leads?**
- Try different search terms
- Expand to adjacent neighborhoods
- Look at different business types

**Contacts hard to find?**
- Check LinkedIn
- Look for press mentions
- Try the business Instagram DM as backup

**Emails feeling generic?**
- Research the business more first
- Add a very specific observation
- Mention a neighborhood connection
