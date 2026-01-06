# Lead Generation Prompts

Reusable prompts for Claude Code to help with lead generation tasks.

---

## Quick Lead Discovery Commands

Copy-paste these directly into Claude Code:

### Daily Quick Search
```
Find 5 new restaurant or cafe openings in Manhattan from the past 2 weeks. Get name, location, Instagram, and any contact info. Save to outputs/leads_[date].md
```

### Neighborhood Blitz
```
Search for new businesses in [Williamsburg/Bushwick/LES/etc] - restaurants, cafes, retail stores. Find ones that opened in the last 60 days. Prioritize ones with visible wall space in photos.
```

---

## Discovery Prompts

### Find New Restaurant Openings

```
Search for new restaurant openings in [NEIGHBORHOOD/CITY] using these sources:

SEARCH QUERIES (run all of these):
1. "new restaurant [neighborhood] 2026"
2. "now open [neighborhood] restaurant"
3. "[neighborhood] restaurant opening"
4. site:eater.com "[neighborhood]" opening
5. site:theinfatuation.com "[neighborhood]" new
6. site:timeout.com new york "[neighborhood]" restaurant

For each result, find:
- Restaurant name and cuisine type
- Exact address
- Opening date (or "coming soon")
- Owner/chef names
- Instagram handle
- Any interior photos showing walls
- Contact info (website, email, phone)

PRIORITIZE restaurants that:
- Opened in last 60 days (or opening soon)
- Have large visible wall space
- Trendy/artistic/design-forward aesthetic
- Independent (not chains)
- Upscale casual or higher price point

Save top 10 to outputs/leads_restaurants_[date].md
```

### Find Coffee Shops & Cafes

```
Search for new coffee shops, cafes, and bakeries in [AREA]:

SEARCH QUERIES:
1. "new coffee shop [area] 2026"
2. "cafe opening [area]"
3. "[area] specialty coffee new"
4. site:sprudge.com "[city]" opening
5. site:perfectdailygrind.com "[city]" new cafe

ALSO CHECK:
- Instagram hashtags: #[neighborhood]coffee, #[city]cafe
- Yelp "Newly Opened" filter for the area
- Google Maps "coffee" sorted by newest

For each, find:
- Name and concept
- Address
- Instagram (check follower count)
- Interior photos
- Owner info if available
- Website/contact

PRIORITIZE:
- Specialty/third-wave coffee (not Starbucks vibes)
- Visible wall space
- Design-conscious interiors
- Active Instagram presence

Save to outputs/leads_cafes_[date].md
```

### Find Breweries & Bars

```
Search for new breweries, taprooms, wine bars, and cocktail bars in [AREA]:

SEARCH QUERIES:
1. "new brewery [area] 2026"
2. "taproom opening [area]"
3. "[area] cocktail bar new"
4. "[area] wine bar opening"
5. site:punchdrink.com "[city]" new bar
6. site:vinepair.com "[city]" brewery

For each, find:
- Name and type (brewery/bar/wine bar)
- Address
- Instagram
- Interior photos (look for large walls, blank spaces)
- Concept/vibe
- Owner names
- Contact info

PRIORITIZE:
- Craft/independent (not big chains)
- Large taproom or bar space
- Industrial or artistic aesthetic
- Active social presence

Save to outputs/leads_bars_[date].md
```

### Find Retail & Boutiques

```
Search for new retail stores, boutiques, and shops in [AREA]:

SEARCH QUERIES:
1. "new store opening [area] 2026"
2. "[area] boutique opening"
3. "new retail [area]"
4. "[area] shop grand opening"

TYPES TO LOOK FOR:
- Fashion boutiques
- Home goods/furniture stores
- Fitness studios/gyms
- Salons and spas
- Plant shops
- Record stores
- Bookstores

For each, find:
- Name and type
- Address
- Instagram
- Interior photos
- Owner info
- Website

PRIORITIZE:
- Design-forward aesthetics
- Local/independent
- Large wall space visible
- Premium positioning

Save to outputs/leads_retail_[date].md
```

### Find Office & Corporate Leads

```
Search for companies with new or renovated offices in [AREA]:

SEARCH QUERIES:
1. "[company type] new office [city] 2026"
2. "[city] office relocation tech startup"
3. "new headquarters [city]"
4. site:commercialobserver.com "[city]" lease
5. site:therealdeal.com "[city]" office

COMPANY TYPES TO TARGET:
- Tech startups (Series A+)
- Creative/design agencies
- Architecture firms
- Media companies
- Co-working spaces
- VC/investment firms

For each, find:
- Company name
- New office address
- Industry/what they do
- Size (employees)
- Key people (CEO, Office Manager, Head of People)
- LinkedIn company page
- Any press about the move

PRIORITIZE:
- Companies mentioning "culture" or "workspace design"
- Creative industries
- Well-funded startups
- Companies with design-forward branding

Save to outputs/leads_corporate_[date].md
```

### Find Hotels & Hospitality

```
Search for new hotels, boutique hotels, and hospitality venues in [AREA]:

SEARCH QUERIES:
1. "new hotel opening [city] 2026"
2. "boutique hotel [city] opening"
3. "[city] hotel renovation"
4. site:hospitalitydesign.com "[city]"

For each, find:
- Hotel name and brand
- Address
- Opening date
- Management company
- Interior designer (if mentioned)
- Instagram
- Press contact

PRIORITIZE:
- Boutique/independent hotels
- Lifestyle brands
- Hotels mentioning local art or design
- Lobby or common area spaces

Save to outputs/leads_hotels_[date].md
```

### Find Public Art Opportunities

```
Search for current public art calls and mural opportunities:

SEARCH QUERIES:
1. "[city] public art call 2026"
2. "[city] mural RFP"
3. "call for artists [city] mural"
4. "[city] percent for art"
5. site:callforentry.org "[city]" mural
6. site:nyc.gov "public art" call

CHECK THESE SOURCES DIRECTLY:
- NYC Department of Cultural Affairs
- Brooklyn Arts Council
- NYC Parks Percent for Art
- MTA Arts & Design
- Local community boards

For each opportunity, find:
- Sponsoring organization
- Project name/description
- Deadline
- Budget (if listed)
- Location/site
- Eligibility requirements
- How to apply
- Contact info

Save to outputs/public_art_opportunities.md
```

---

## NYC Neighborhood Targeting

### Manhattan Neighborhoods (High Opportunity)
- **NoHo/SoHo** — Design-forward, high budget
- **Lower East Side** — Trendy restaurants, bars
- **West Village** — Boutiques, upscale casual
- **East Village** — Bars, creative spaces
- **Tribeca** — High-end restaurants
- **Chelsea** — Galleries, creative offices
- **Flatiron/NoMad** — Tech offices, upscale hospitality
- **Midtown** — Corporate, hotels

### Brooklyn Neighborhoods (High Opportunity)
- **Williamsburg** — Everything, very competitive
- **Bushwick** — Breweries, creative spaces
- **Greenpoint** — Cafes, boutiques
- **DUMBO** — Tech offices, upscale
- **Crown Heights** — Restaurants, cafes
- **Park Slope** — Family-friendly retail, restaurants
- **Cobble Hill/Boerum Hill** — Boutiques, restaurants

### Jersey/Other
- **Jersey City** — Growing restaurant scene
- **Hoboken** — Bars, restaurants
- **Astoria** — Diverse restaurants

---

## Research Prompts

### Deep Research on a Business

```
Research [BUSINESS NAME] thoroughly for a mural pitch:

FIND THIS INFO:
1. Owner/founder name
2. Email (check: website, LinkedIn, press releases, Hunter.io)
3. Phone number
4. Instagram handle + follower count
5. When they opened
6. Business concept/story
7. Design firm that did their space (if any)
8. Interior photos — especially blank walls
9. Press coverage
10. Their vibe/values

ALSO CHECK:
- Do they already have murals or art?
- Have they mentioned art or local artists anywhere?
- Are they expanding to new locations?
- What's their design aesthetic?

Save to outputs/research_[business-name].md
```

### Find Contact Info

```
Find contact information for [BUSINESS NAME] in [LOCATION]:

PRIORITY ORDER:
1. Owner/founder direct email
2. General manager email
3. General inquiry email
4. Phone number
5. Contact form URL
6. Instagram DM (backup)

SEARCH THESE:
- Website: About, Contact, Press, Team pages
- LinkedIn: Owner/manager profiles
- Press releases mentioning the business
- Yelp business info
- Google Maps listing
- Secretary of State business filings (for owner name)
- Instagram bio

Note where each piece of info was found.
```

### Competitive Research

```
Research recent mural projects in [AREA] to find similar opportunities:

1. Search: "[area] new mural 2026" and "muralist [area] project"
2. Check Instagram: #[area]mural, #[city]murals
3. Find which businesses recently got murals
4. Identify similar businesses nearby WITHOUT murals
5. Those are your leads

For each potential lead:
- Business name and type
- Location
- Why they're similar to one that got a mural
- Contact info

Save to outputs/competitive_leads.md
```

---

## Drafting Prompts

### Draft Pitch Email

```
Draft a personalized pitch email for [BUSINESS NAME].

CONTEXT:
- Business type: [restaurant/cafe/office/etc]
- Location: [neighborhood]
- Recently: [opened/expanded/renovated]
- Specific observation: [what you noticed about them]
- Relevant past project: [similar work I've done]

USE MY CASE STUDIES:
- Namkeen: 3 locations, repeat client
- Haraz Coffee: ceiling mural visible from outside, drove foot traffic
- TikTok: social impact mural on commercial building

REQUIREMENTS:
- Under 150 words
- Lead with something specific about THEM
- Mention relevant similar project with results
- Include portfolio link
- Conversational but professional tone
- Soft call to action

Save to outputs/drafts/[business-name]_pitch.md
```

### Draft Follow-Up Email

```
Draft a follow-up email for [BUSINESS NAME].

Original outreach was sent [DATE/TIMEFRAME] with no response.

KEEP IT:
- Under 75 words
- Friendly, not pushy
- Offer an easy out ("if timing isn't right")
- Leave door open for future

Save to outputs/drafts/[business-name]_followup.md
```

---

## Tracking Prompts

### Weekly Lead Summary

```
Summarize my lead generation this week:

Look at all files in outputs/ from past 7 days:

1. Total new leads (by category)
2. Leads with complete contact info
3. Pitches drafted
4. Any patterns in what's working
5. Priority leads for next week

Format as a brief report.
```

### Pipeline Status

```
Review my lead pipeline:

Go through outputs/ and categorize leads:
- New (not contacted)
- Contacted (awaiting response)
- Responded (in conversation)
- Not interested
- Won (project booked)

Flag leads needing follow-up (contacted >5 days ago, no response).
```

---

## Search Query Cheatsheet

### For New Openings
```
"new restaurant [neighborhood] 2026"
"[neighborhood] opening soon"
"now open [neighborhood]"
site:eater.com [city] openings
site:theinfatuation.com [neighborhood] new
site:timeout.com [city] new restaurant
site:ny.eater.com "[neighborhood]"
```

### For Contacts
```
"[business name]" owner
"[business name]" founder
"[business name]" email
"[owner name]" email [city]
site:linkedin.com "[business name]" [city]
```

### For Public Art
```
[city] public art call 2026
[city] mural RFP artist
"call for artists" [city] mural
site:callforentry.org [city]
```

### For Instagram Research
```
site:instagram.com "[business name]"
#[neighborhood]eats
#[neighborhood]coffee
#[city]restaurants
#[city]newrestaurant
```

### For Competitive Intel
```
"[neighborhood] mural" 2026
muralist [neighborhood] project
"new mural" [city]
site:instagram.com [neighborhood] mural
```
