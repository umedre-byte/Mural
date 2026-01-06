# Lead Generation Prompts

Reusable prompts for Claude Code to help with lead generation tasks.

---

## IMPORTANT: Lead Qualification Criteria

Before adding ANY lead, verify they meet these criteria:

### Must-Have Signals (at least 2):
1. **New/Renovating** — Opened in last 90 days OR currently renovating
2. **Social Presence** — Active Instagram (posts in last 30 days, 500+ followers)
3. **Visual Brand** — Website/social shows they care about aesthetics
4. **Large Wall Space** — Visible blank walls in photos
5. **Community Focus** — Local, independent, community-oriented

### Strong Conversion Signals:
- Mentioned "art," "design," "local artists," or "community" anywhere
- Recently posted about renovations or new space
- Other locations have murals
- Competitors nearby have murals
- Premium positioning (upscale casual+)
- Active engagement on social (not dead accounts)

### Disqualify If:
- Chain/franchise (unless local franchise owner)
- No social media presence at all
- Last Instagram post 6+ months ago
- Already has murals everywhere
- Budget indicators are low (very cheap, discount-focused)

---

## Quick Lead Discovery Commands

Copy-paste these directly into Claude Code:

### Daily Quick Search
```
Find 5 new restaurant or cafe openings in [CITY] from the past 2 weeks.
Verify each has: active Instagram, visible wall space, design-conscious aesthetic.
Get name, location, Instagram, and contact info.
Save to outputs/leads_[date].md
```

### Neighborhood Blitz
```
Search for new businesses in [AREA] - restaurants, cafes, commercial spaces.
Find ones opened in last 60 days.
QUALIFY EACH: Check Instagram is active, look for blank walls in photos, verify they care about aesthetics.
Only include qualified leads.
```

### USA-Wide Search
```
Search for [BUSINESS TYPE] openings across major US cities: NYC, LA, Chicago, Miami, Austin, Denver, Seattle, Portland, Atlanta, Dallas.
Focus on: new openings, renovations, expansions.
MUST verify social presence and mural-readiness before including.
Save to outputs/leads_usa_[date].md
```

---

## Discovery Prompts

### Find New Restaurant Openings (USA-Wide)

```
Search for new restaurant openings in [CITY] or across multiple cities:

SEARCH QUERIES (run all of these):
1. "new restaurant [city] 2026"
2. "now open [city] restaurant"
3. "[city] restaurant opening"
4. site:eater.com "[city]" opening 2026
5. site:theinfatuation.com "[city]" new
6. "[city] restaurant grand opening"

For each result, find:
- Restaurant name and cuisine type
- Exact address
- Opening date (or "coming soon")
- Owner/chef names
- Instagram handle + check if active
- Interior photos — LOOK FOR BLANK WALLS
- Contact info (website, email, phone)

QUALIFICATION CHECKLIST (must pass):
☐ Opened in last 90 days (or opening soon)
☐ Instagram is ACTIVE (posted in last 30 days)
☐ Has 500+ followers OR strong engagement
☐ Interior shows wall space available
☐ Independent (not a chain)
☐ Design-conscious aesthetic
☐ Upscale casual or higher

BONUS SIGNALS (higher priority):
- Mentioned "art" or "local" anywhere
- Chef/owner has media presence
- Multiple locations (repeat client potential)
- Competitors nearby have murals

DO NOT INCLUDE:
- Chains or franchises
- Dead Instagram (no posts in 6+ months)
- Fast food / quick service
- Discount-focused branding

Save QUALIFIED leads only to outputs/leads_restaurants_[date].md
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

### Find Masjids & Islamic Centers

```
Search for masjids, mosques, and Islamic centers that may need murals or calligraphy:

SEARCH QUERIES:
1. "new masjid opening [city] 2026"
2. "new mosque [city]"
3. "islamic center renovation [city]"
4. "masjid expansion [city]"
5. "muslim community center [city] new building"

TARGET CITIES (large Muslim populations):
- NYC, NJ (Paterson, Jersey City)
- Detroit/Dearborn, MI
- Chicago, IL
- Houston, TX
- Dallas, TX
- Los Angeles, CA
- Atlanta, GA
- Philadelphia, PA
- DMV (DC, Maryland, Virginia)
- Minneapolis, MN

LOOK FOR:
- New construction or major renovations
- Community fundraising for new space
- Recently completed buildings needing interior art
- Centers mentioning "beautification" or "design"
- Active social media presence

For each, find:
- Masjid/center name
- Location
- Website
- Social media (Facebook often more active than Instagram)
- Board contact or imam name
- Recent news about construction/renovation
- Community size indicators

QUALIFICATION CHECK:
- Is this a new or renovated space?
- Do they have fundraising capacity?
- Are they active on social media?
- Have they mentioned art, calligraphy, or beautification?

NOTE: Aml has experience with Islamic calligraphy and worked with Spiritual Society of Canada. This is a specialty niche.

Save to outputs/leads_masjids_[date].md
```

### Find Commercial Spaces & Offices (USA-Wide)

```
Search for commercial spaces needing murals across major US cities:

SEARCH QUERIES:
1. "new office opening [city] 2026"
2. "coworking space opening [city]"
3. "tech startup new headquarters [city]"
4. "creative agency new office [city]"
5. site:commercialobserver.com [city] lease creative

TARGET CITIES:
- NYC, LA, Chicago, Miami, Austin, Denver, Seattle, Portland, Atlanta, Dallas, San Francisco, Boston, Nashville, Phoenix

TYPES OF COMMERCIAL SPACES:
- Tech company offices
- Creative/design agencies
- Coworking spaces (WeWork competitors)
- Startup headquarters
- Media companies
- Architecture firms
- Marketing agencies

QUALIFICATION CRITERIA:
- Recently moved or opened (last 6 months)
- Active LinkedIn company page
- Website shows design-conscious brand
- Mentioned "culture," "workspace," or "creative" in job posts
- Well-funded (Series A+ for startups)

For each, find:
- Company name
- Office address
- Industry
- Key decision makers (CEO, Head of People, Office Manager)
- LinkedIn page
- Company size
- Any press about the move

Save to outputs/leads_commercial_usa_[date].md
```

### Find Public Art Opportunities (USA-Wide)

```
Search for public art calls and mural opportunities across the USA:

SEARCH QUERIES:
1. "[city] public art call 2026"
2. "[city] mural RFP"
3. "call for artists [city] mural"
4. "[state] percent for art"
5. site:callforentry.org mural [year]
6. site:publicartarchive.org opportunities

CHECK THESE SOURCES:
- Americans for the Arts public art network
- Call for Entry (cafe.org)
- Public Art Archive
- City cultural affairs departments
- State arts councils
- Local community development organizations

TARGET CITIES WITH ACTIVE PUBLIC ART PROGRAMS:
- NYC, LA, Chicago, Philadelphia, Denver, Austin, Miami, Seattle, Portland, Atlanta, San Francisco, Boston, Minneapolis

For each opportunity, find:
- Sponsoring organization
- Project name/description
- Deadline
- Budget (if listed)
- Location/site
- Eligibility (local artist requirements?)
- Application requirements
- Contact info

Save to outputs/public_art_usa_[date].md
```

---

## USA City Targeting

### Tier 1 Cities (Highest Opportunity)
- **New York City** — All boroughs, highest volume
- **Los Angeles** — Arts district, West Hollywood, DTLA
- **Chicago** — Wicker Park, Logan Square, West Loop
- **Miami** — Wynwood, Design District, Brickell
- **Austin** — East Austin, South Congress, downtown

### Tier 2 Cities (Strong Markets)
- **Denver** — RiNo, LoDo, Capitol Hill
- **Seattle** — Capitol Hill, Fremont, Ballard
- **Portland** — Alberta, Pearl District, Division
- **Atlanta** — Old Fourth Ward, Ponce City, Westside
- **Dallas** — Deep Ellum, Design District, Bishop Arts
- **San Francisco** — Mission, SOMA, Hayes Valley
- **Nashville** — East Nashville, The Gulch, 12 South
- **Philadelphia** — Fishtown, Northern Liberties, Rittenhouse

### Emerging Markets
- **Phoenix** — Roosevelt Row, downtown
- **Charlotte** — NoDa, South End
- **Detroit** — Corktown, Midtown
- **Minneapolis** — Northeast, North Loop
- **San Diego** — North Park, Barrio Logan

### Masjid/Islamic Center Hotspots
- **NYC/NJ** — Paterson, Jersey City, Jackson Heights
- **Detroit/Dearborn** — Largest Arab-American population
- **Chicago** — Devon Ave, Bridgeview
- **Houston/Dallas** — Large Muslim communities
- **DMV** — Falls Church, Fairfax, Baltimore
- **Los Angeles** — Anaheim, Irvine, LA proper
- **Minneapolis** — Cedar-Riverside (Somali community)
- **Atlanta** — Clarkston, Decatur

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
