# VVD Dalfsen Campaign Website

## Project Overview
Hugo static website for the VVD Dalfsen political party's 2026 municipal election campaign.
- **URL**: www.vvddalfsen.nl
- **Language**: Dutch (nl-nl)
- **Tagline**: "Vrij denken, lokaal doen" (Free thinking, acting locally)

## Tech Stack
- **Static Site Generator**: Hugo (v0.55.0+ extended required)
- **Theme**: Hugo Serif Theme (ZeroStatic)
- **Styling**: SCSS with VVD brand colors (orange #f50, blue #0A2CCA)
- **Deployment**: GitHub Pages via GitHub Actions (on push to main)
- **Fonts**: Playfair Display (headings), Source Sans Pro (body)

## Project Structure
```
content/
├── _index.md              # Homepage
├── contact.md             # Contact page
├── programma/             # Election manifesto (8 policy documents)
└── team/                  # Candidate profiles (10 people)
themes/hugo-serif-theme/   # Main theme
static/images/             # Logos, team photos, illustrations
config.toml                # Hugo configuration
```

## Content Sections

### Programma (Election Manifesto)
8 policy areas:
1. Economie en ondernemerschap (Economy & entrepreneurship)
2. Zorg en samenleving (Healthcare & society)
3. Duurzaamheid (Sustainability)
4. Onderwijs (Education)
5. Wonen en leefbaarheid (Housing & livability)
6. Veiligheid en bereikbaarheid (Safety & accessibility)
7. Bestuur en financien (Governance & finance)
8. De kracht van Dalfsen (Dalfsen's strength)

### Team (Candidates)
10 candidates with profile photos, bios, contact info, and ballot positions.

## Development Commands
```bash
hugo server          # Local dev server
hugo                 # Build site to /public
```

## Deployment
Automatic via GitHub Actions on push to `main` branch. Workflow builds with Hugo Extended v0.128.0 and deploys to GitHub Pages.
