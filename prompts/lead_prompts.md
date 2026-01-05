# Lead Generation Prompts

Reusable prompts for Claude Code to help with lead generation tasks.

---

## Discovery Prompts

### Find New Restaurant Openings

```
Search for new restaurant openings in [NEIGHBORHOOD/CITY] from the past 30 days.

Look for:
- Restaurant name and type of cuisine
- Location/address
- Opening date (or "coming soon")
- Owner names if mentioned
- Any photos showing the interior/walls
- Their Instagram handle

Focus on restaurants that appear to have:
- Visible wall space
- Trendy/artistic aesthetic
- Local/artisanal focus
- Budget for design (upscale casual or higher)

Save the top 10 most promising leads to outputs/leads_restaurants_[date].md
```

### Find Brewery/Coffee Shop Leads

```
Search for new breweries, taprooms, and specialty coffee shops in [AREA].

For each, find:
- Business name
- Location
- Opening status (open, coming soon, recently opened)
- Social media presence
- Any visible interior photos
- Contact information if available

Prioritize:
- Craft/independent establishments
- Those with visible wall space
- Active Instagram presence
- Neighborhood-focused concepts

Save to outputs/leads_hospitality_[date].md
```

### Find Office/Corporate Leads

```
Search for companies that recently moved to or opened new offices in [CITY/AREA].

Focus on:
- Tech startups and scale-ups
- Creative agencies
- Architecture and design firms
- Companies mentioning "office culture" or workspace design
- Co-working spaces

For each, find:
- Company name
- Office location
- Industry/what they do
- LinkedIn presence
- Any news about their move/expansion
- Who handles facilities/office design

Save to outputs/leads_corporate_[date].md
```

### Find Public Art Opportunities

```
Search for current public art calls and mural opportunities:

Look for:
- City/municipal art programs
- "Percent for art" projects
- Community mural programs
- Corporate public art RFPs
- Developer public art requirements

For each opportunity, find:
- Sponsoring organization
- Deadline
- Location/site
- Budget if listed
- Application requirements
- Contact information

Focus on [CITY/REGION] and surrounding areas.

Save to outputs/public_art_opportunities.md
```

---

## Research Prompts

### Deep Research on a Business

```
Research [BUSINESS NAME] thoroughly for a mural pitch:

Find:
1. Owner/decision maker name
2. Email address (check website, LinkedIn, press releases)
3. Phone number
4. Instagram handle and follower count
5. Business concept/story
6. Interior photos (especially walls)
7. Design aesthetic
8. Any press coverage
9. When they opened
10. Their values/what they care about

Also look for:
- Any existing art on their walls
- Mentions of local artists or community
- Design firm that did their space
- Any planned expansions

Save to outputs/research_[business-name].md
```

### Find Contact Info

```
Find contact information for [BUSINESS NAME] in [LOCATION]:

Priority order:
1. Owner/founder direct email
2. General manager email
3. Contact form on website
4. Phone number
5. Instagram DM (as backup)

Search:
- Their website (especially About, Contact, Press pages)
- LinkedIn profiles of owners/managers
- Press releases mentioning them
- Business registration records
- Yelp business info

Note the source of each piece of contact info found.
```

### Competitive Research

```
Research recent mural projects in [AREA] to find similar opportunities:

1. Search for muralists who completed projects in the last 6 months
2. Identify the businesses they worked with
3. Look for similar businesses nearby that don't have murals yet

For each potential lead found:
- Business name and type
- Location
- Why they might want a mural (similar to business that got one)
- Contact info if available

Save to outputs/competitive_leads.md
```

---

## Drafting Prompts

### Draft Pitch Email

```
Draft a personalized pitch email for [BUSINESS NAME].

Context:
- Business type: [restaurant/cafe/office/etc]
- Location: [neighborhood]
- Recently: [opened/expanded/renovated]
- Specific observation: [what you noticed about them]
- Relevant past project: [similar work you've done]

Use the [restaurant/cafe/office] template from templates/email_templates.md as a base.

Requirements:
- Under 150 words
- Reference something specific about their business
- Mention relevant similar project
- Include portfolio link
- Clear call to action
- Match their vibe (casual/professional)

Save draft to outputs/drafts/[business-name]_pitch.md
```

### Draft Follow-Up Email

```
Draft a follow-up email for [BUSINESS NAME].

Original outreach was sent [DATE/TIMEFRAME] with no response.

Keep it:
- Brief (under 75 words)
- Friendly, not pushy
- Offering an easy out ("if timing isn't right")
- Leaving door open for future

Save to outputs/drafts/[business-name]_followup.md
```

### Draft Warm Introduction Email

```
Draft an introduction email for [BUSINESS NAME].

Context:
- Referred by: [MUTUAL CONTACT]
- How referrer knows them: [relationship]
- What referrer said: [any context given]

Make it feel warm and personal, mention the mutual connection prominently.

Save to outputs/drafts/[business-name]_intro.md
```

---

## Tracking Prompts

### Weekly Lead Summary

```
Summarize my lead generation activity this week:

Look at all files in outputs/ from the past 7 days and provide:

1. Total new leads found (by category)
2. Leads with complete contact info
3. Pitches drafted
4. Any patterns in what's working
5. Recommended priorities for next week

Format as a brief weekly report.
```

### Lead Pipeline Status

```
Review my current lead pipeline:

Go through outputs/ folder and categorize all leads by status:
- New (not yet contacted)
- Contacted (awaiting response)
- Responded (in conversation)
- Not interested
- Won (project booked)

List each with last action date.

Flag any leads that need follow-up (contacted >5 days ago, no response).
```

---

## Search Strategies

When Claude Code searches, use these patterns:

**For new openings:**
- `"[city] new restaurant opening 2025"`
- `"[neighborhood] restaurant coming soon"`
- `"[city] brewery opening"`
- `site:eater.com [city] openings`
- `site:instagram.com [neighborhood] new restaurant`

**For contacts:**
- `"[business name]" owner`
- `"[business name]" founder email`
- `site:linkedin.com "[business name]" [city]`
- `"[owner name]" email [city]`

**For public art:**
- `[city] public art call for artists`
- `[city] mural program application`
- `"percent for art" [city] [year]`
- `site:callforentry.org [city] mural`

**For competitive intel:**
- `[neighborhood] mural artist`
- `"new mural" [city] [year]`
- `site:instagram.com [city] mural reveal`
