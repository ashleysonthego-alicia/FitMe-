# FitMe 🏖️

A gamified health & fitness mobile web app built from the FitMe Functional Requirements Document (FRD).

## Overview

FitMe is a personalized health journey app that combines gamification, AI coaching, and evidence-based nutrition/exercise guidelines to help users reach their weight and wellness goals.

## Features

### Onboarding (FR-01, FR-01.01–01.03)
- Name, age, gender, units (lbs default), current/goal weight, target date (defaults to 1 year out)
- Full allergy & sensitivity selection (Milk, Eggs, Wheat, Peanuts, Tree Nuts, Soybeans, Sesame, Fish, Shellfish, Vegetarian, Vegan, Diabetes)
- Six World themes: Beach, City, Country, Forest, Mountain, Sci-Fi
- Activity preferences & temptations selection
- Photo upload with local-only privacy guarantee
- Push notification opt-in

### Gamified Path (FR-02, FR-02.02–02.07)
- Stepping-stone path with completed, current, and locked states
- Task stones: Meal Plan, Stretch, Meals (B/L/D), Hydration, Breathing, Exercise, Snack, Walk, Temptation avoidance
- Day and week dividers along the path
- Streak counter and shell balance in the header
- Stock Up (shopping list) and Meal Prep weekly actions (FR-10)

### Kit — AI Partner (FR-13, FR-13.01–13.03)
- Conversational AI wellness partner with voice input support
- Quick-reply prompts for common check-ins
- Contextual, empathetic responses for meals, exercise, hydration, and motivation
- Named "Kit" per FRD specification

### Avatar Shop (FR-06.01, FR-09, FR-09.01, FR-02.06)
- Theme-appropriate currency (shells for Beach World)
- Accessories: 500 shells | Outfits: 1,500 shells | Experiences: 5,000 shells
- 6–8 items per tier, themed to selected World

### Profile & Progress (FR-07, FR-09.01)
- Live streak, shells, and weight-lost stats
- Progress bars for daily tasks, hydration, and weight goal
- Full shell earning rate guide

### Security & Privacy (FR-04, FR-12)
- All photos stored locally only
- No nude/suggestive image policy enforced at upload
- Settings panel with privacy & data controls

## Point / Shell Earning Guide

| Activity | Shells |
|---|---|
| Healthy meal (B/L/D) | +15 |
| Avoid a temptation | +10 |
| Drink water (per 8oz) | +3 |
| Walk after meal | +10 |
| Aerobic exercise (per 10 min) | +20 |
| Stretching (per 5 min) | +5 |
| 4-7-8 breathing (per minute) | +1 |
| Meal Plan / Stock Up / Meal Prep (weekly) | +20 |
| Streak (any 1 task/day) | +1 |

## Shop Tiers

| Tier | Cost |
|---|---|
| Accessories | 500 shells |
| Outfits | 1,500 shells |
| Experiences | 5,000 shells |

## Health Guidelines Referenced

- [American Heart Association — Healthy Eating](https://www.heart.org/en/healthy-living/healthy-eating/eat-smart)
- [American Heart Association — Physical Activity](https://www.heart.org/en/healthy-living/fitness/fitness-basics/aha-recs-for-physical-activity-in-adults)
- [American Diabetes Association — Meal Planning](https://diabetes.org/food-nutrition/meal-planning)
- [Harvard Medical School — Types of Exercise](https://www.health.harvard.edu/exercise-and-fitness/the-4-most-important-types-of-exercise)
- [Harvard Health — Hydration](https://www.health.harvard.edu/healthy-aging-and-longevity/how-much-water-should-you-drink)

## Tech Stack

- Pure HTML/CSS/JavaScript — no build step required
- Self-contained single-file app (`index.html`)
- [Tabler Icons](https://tabler.io/icons) webfont for UI icons
- Runs in any modern browser, optimized for mobile (390px viewport)

## Running Locally

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/fitme.git
cd fitme

# Open in browser (no server needed)
open index.html
# or
python3 -m http.server 8080
```

## Project Structure

```
fitme/
├── index.html      # Complete app (HTML + CSS + JS)
└── README.md       # This file
```

## Roadmap (from FRD)

- [ ] AI-generated weight-loss progression images (FR-01, FR-05)
- [ ] Cartoon avatar generation from uploaded photo
- [ ] GenAI meal plan generation via API
- [ ] Push notification service integration (FR-13)
- [ ] Location-aware temptation alerts (FR-13.03)
- [ ] iOS / Android native wrapper (FR-11)
- [ ] Admin statistics dashboard (FR-04)
- [ ] Cross-device data sync with encryption

## License

Private — All rights reserved.
