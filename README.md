# Tara — Your AI Travel Planner That Remembers How You Travel

> ⚠️ **DRAFT** — This specialist was created on Feb 17, 2026 and has not yet been manually reviewed. Content, structure, and instructions may change.

Every travel app gives the same "top 10" lists. Tara plans trips for **you** — she knows you hate early mornings, love street food, need an aisle seat, and that the Airbnb in Lisbon was a disaster. Every trip she plans is better than the last because she never forgets.

## The Problem

You ask an AI to plan a trip to Japan. It gives you the same generic Shibuya-Senso-ji-Mt. Fuji itinerary everyone gets. It doesn't know you spent a week in Tokyo last year, that you're vegetarian, that you travel with a bad knee, or that you have 200,000 Marriott points to burn. You re-explain everything. Every. Single. Time.

**Tara fixes this.**

## What Tara Does

🗺️ **Personalized Itineraries** — Built around your travel style, pace, budget, and interests — not tourist template #47

📦 **Smart Packing Lists** — Customized by destination climate, trip type, and your personal essentials (she remembers you always forget sunscreen)

💰 **Budget Planning** — Realistic cost estimates, splurge-vs-save advice, and tracking — tailored to your spending style

🏨 **Accommodation Matching** — Hotels, Airbnbs, or hostels based on what you actually prefer and your loyalty program status

🍜 **Food & Experience Recommendations** — Based on your dietary needs, cuisine preferences, and what you've loved (or hated) before

📊 **Trip Learning** — Every trip makes future planning better. Tara debriefs with you and remembers what worked.

## How It Works

Tara is an **AI Specialist** built on [Magic Context](https://magiccontext.ai). Instead of starting every AI conversation from scratch, Tara maintains a persistent workspace — your traveler profile, trip history, preferences, and loyalty programs — that carries across every session.

```
┌──────────────────────────────────────────┐
│          Tara's Workspace                │
├──────────────────────────────────────────┤
│                                          │
│  📋 AI Instructions                      │
│  ├── Planning personality & approach     │
│  ├── Travel expertise                    │
│  └── Memory protocols                    │
│                                          │
│  🧠 Memory                               │
│  ├── Traveler profile & health needs     │
│  ├── Preferences & loyalty programs      │
│  └── Trip history & reviews              │
│                                          │
│  📚 Knowledge Base                       │
│  ├── Travel tips & booking strategies    │
│  ├── Destination research frameworks     │
│  ├── Packing guides by climate & type    │
│  └── Budget planning & tracking          │
│                                          │
│  🎯 Active Projects                      │
│  ├── Upcoming trips                      │
│  └── Destination wishlist                │
│                                          │
│  📝 Templates                            │
│  ├── Trip plans                          │
│  ├── Daily itineraries                   │
│  └── Packing lists                       │
│                                          │
└──────────────────────────────────────────┘
```

### The Magic Context Difference

Traditional AI is **stateless** — it forgets everything between conversations. Magic Context gives AI specialists **persistent memory** through structured workspaces. This means:

- **Session 1:** Tara learns how you travel — style, pace, budget, dietary needs, loyalty programs
- **Session 5:** Tara plans a trip that avoids the things you didn't like last time and doubles down on what you loved
- **Session 20:** Tara knows your travel patterns better than you do — seasonal preferences, ideal trip length, packing habits
- **Session 50+:** Tara is a travel agent who's planned every trip you've taken, with perfect recall of every detail

**Your context is yours.** It's stored as plain markdown files you can read, edit, or export anytime. No black box. No vendor lock-in.

## Quick Start

### Import to AI Specialists Hub

```bash
# Via the Magic Context import feature
import_specialist github.com/magic-context/tara-travel-planner
```

Or use the import tool in [AI Specialists Hub](https://aispecialistshub.com) with:
```
https://github.com/magic-context/tara-travel-planner
```

### First Session

Tara will guide you through a traveler intake:
1. Your travel style and pace
2. Budget range and preferences
3. Dietary needs and mobility considerations
4. Accommodation and activity preferences
5. Past trips and dream destinations
6. Loyalty programs and points

Then she'll help plan your next adventure.

### Ongoing Use

- **Trip planning** — Complete itineraries from flights to daily activities
- **Destination research** — Compare options based on your preferences
- **Packing lists** — Customized for every trip
- **Budget tracking** — Plan and track trip costs
- **Post-trip debriefs** — What worked, what to skip next time

## Repository Structure

```
tara-travel-planner/
├── configuration/
│   └── module.json              # Specialist metadata
├── content/
│   ├── README.md               # Workspace guide
│   ├── ai-instructions/        # Tara's planning brain
│   │   ├── core-instructions.md
│   │   ├── getting_started.md
│   │   └── memory-protocols.md
│   ├── memory/                 # Your traveler profile
│   │   ├── user-profile.md
│   │   └── preferences.md
│   ├── knowledge/              # Travel expertise
│   │   ├── travel-tips.md
│   │   ├── destination-research.md
│   │   ├── packing-guides.md
│   │   ├── budget-planning.md
│   │   └── templates/
│   │       ├── trip-plan.md
│   │       ├── daily-itinerary.md
│   │       └── packing-list.md
│   ├── active-projects/        # Upcoming trips
│   │   └── current-goals.md
│   ├── historical/             # Past trips
│   └── feedback/               # Improvement notes
└── README.md
```

## Who This Is For

- **Frequent travelers** who want consistent, personalized planning that improves over time
- **Families** juggling different needs (kids, dietary restrictions, mobility) across every trip
- **Couples** who plan together and want someone to remember both preferences
- **Anyone tired of re-explaining their travel style** to AI every single session

## Suggested MCP Skill Pairings

Tara works with any MCP-compatible AI agent (Claude, GPT, Gemini, etc.). These integrations enhance the experience:

- **Weather Service** — Check destination forecasts for trip timing and packing
- **Location / Places Search** — Discover restaurants and attractions near your accommodation
- **Visual Display** — Display itineraries, maps, and trip dashboards
- **Email Integration** — Monitor booking confirmations and flight changes
- **Project Management & Notes** — Organize detailed trip plans and travel journals

## Requirements

- [AI Specialists Hub](https://aispecialistshub.com) account (or any Magic Context-compatible platform)
- ChatGPT Plus/Pro/Team/Enterprise OR Claude with MCP support

## Contributing

Feedback and improvements welcome via issues. This is a showcase specialist for Magic Context — if Tara makes your trips better, imagine what a persistent AI specialist could do for *your* domain.

## License

MIT

---

Built with [Magic Context](https://magiccontext.ai) — Context as a Service for AI
