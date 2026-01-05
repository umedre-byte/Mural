# Mural Lead Generation Agent for Claude Code

A lead generation system designed for muralists to find new business opportunities. Built to run entirely within Claude Code.

## Overview

This agent helps you:
1. **Discover opportunities** - Find new restaurants, offices, and venues that might need murals
2. **Extract contacts** - Get business contact information
3. **Draft pitches** - Generate personalized outreach emails

## Project Structure

```
mural-lead-agent/
├── README.md                 # This file
├── CLAUDE.md                 # Instructions for Claude Code
├── config/
│   └── artist_profile.json   # Your muralist profile & portfolio info
├── prompts/
│   └── lead_prompts.md       # Prompts for Claude Code to use
├── templates/
│   └── email_templates.md    # Email pitch templates
└── outputs/
    └── .gitkeep              # Leads and drafts will be saved here
```

## Setup Instructions

### 1. Configure Your Artist Profile

Edit `config/artist_profile.json` with your information:
- Your name and business name
- Years of experience
- Specialties (restaurants, offices, residential, etc.)
- Portfolio links
- Location/service area
- Notable past clients

### 2. Using with Claude Code

Open this folder in Claude Code and use natural language commands like:

```
"Find new restaurant openings in Brooklyn that might need murals"
"Search for new office spaces in Manhattan looking for art installations"
"Find breweries or coffee shops that recently opened in NYC"
"Draft a pitch email for [business name]"
```

### 3. Workflow

1. **Discovery**: Ask Claude Code to search for opportunities
2. **Research**: Have Claude Code gather business details and contacts
3. **Outreach**: Generate personalized pitch emails
4. **Track**: Save leads to the outputs folder

## Best Opportunity Types for Muralists

- New restaurant/bar openings
- Brewery taprooms
- Coffee shops and cafes
- Boutique hotels
- Co-working spaces
- Corporate office lobbies
- Retail stores
- Community centers
- Schools and universities
- Healthcare facilities (children's hospitals, wellness centers)
- Real estate developments
- Public art programs

## Tips for Claude Code Usage

Use specific prompts like:
- "Search for '[city] new restaurant opening 2025' and find ones that might want murals"
- "Look up the contact info for [business name] and find the owner or manager email"
- "Draft a warm, professional email pitch for [business] mentioning their [specific detail]"

## Customization

Modify the templates and prompts to match your style and voice. The more specific your artist profile, the better the personalized pitches will be.
