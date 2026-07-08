# FitMe 🏖️

A gamified health & fitness mobile web app built from the FitMe Functional Requirements Document (FRD).

## Overview

FitMe is a personalized health journey app combining gamification, AI coaching, and evidence-based nutrition/exercise guidelines (AHA, Harvard Health, ADA) to help users reach their weight and wellness goals.

## Features

### Onboarding (FR-01, FR-01.01–01.03)
- Name, age, gender, units (lbs default), current/goal weight, target date
- Allergy & sensitivity selection: Milk, Eggs, Wheat, Peanuts, Tree Nuts, Soybeans, Sesame, Fish, Shellfish, Vegetarian, Vegan, Diabetes
- Six World themes: Beach 🏖️, City 🏙️, Country 🌾, Forest 🌲, Mountain 🏔️, Sci-Fi 🚀
- Activity preferences & temptations selection
- Photo upload (local-only) + push notification opt-in

### Gamified Path (FR-02)
- Stepping-stone path: completed ✅, current 🔵, locked 🔒
- 16 daily task stones: Meal Plan, Stretch, Meals (B/L/D), Hydration, Breathing, Exercise, Snack, Walk, Avoid Temptation
- Streak counter and shell balance header
- Stock Up (shopping list) + Meal Prep weekly actions (FR-10)

### Kit — AI Partner (FR-13)
- Conversational AI wellness coach with quick replies and voice input
- Contextual, empathetic responses for meals, exercise, hydration, motivation

### Avatar Shop (FR-09)
- Accessories: 500 shells | Outfits: 1,500 shells | Experiences: 5,000 shells

### Profile & Progress (FR-07)
- Streak, shells, weight-lost stats
- Progress bars: daily tasks, hydration, weight goal
- Full shell earning guide

## Shell Earning Guide

| Activity | Shells |
|---|---|
| Healthy meal (B/L/D) | +15 🐚 |
| Avoid a temptation | +10 🐚 |
| Drink water (per 8oz) | +3 🐚 |
| Walk after meal | +10 🐚 |
| Aerobic exercise (per 10 min) | +20 🐚 |
| Stretching (per 5 min) | +5 🐚 |
| 4-7-8 breathing (per minute) | +1 🐚 |
| Meal Plan / Stock Up / Prep (weekly) | +20 🐚 |

## Tech Stack
- Pure HTML / CSS / JavaScript — zero build step
- Single file: `index.html`
- [Tabler Icons](https://tabler.io/icons) webfont
- Mobile-first, 390px viewport

## Run Locally
```bash
git clone https://github.com/ashleysonthego-alicia/FitMe-.git
cd FitMe-
open index.html          # macOS
# or
python3 -m http.server 8080   # then visit http://localhost:8080
```

## Roadmap (FRD)
- [ ] AI progression photo generation (FR-05)
- [ ] Cartoon avatar from uploaded photo
- [ ] GenAI meal plan via API
- [ ] Push notifications (FR-13)
- [ ] iOS / Android native wrapper (FR-11)
- [ ] Admin dashboard (FR-04)
- [ ] Encrypted cross-device sync

## License
Private — All rights reserved.
