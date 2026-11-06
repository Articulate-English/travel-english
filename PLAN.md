# Travel Vocabulary for Italians - Implementation Plan

## Overview
12-lesson single-file HTML slide deck with:
- Vocabulary exercises with clickable definitions
- "Order the words into a sentence" exercises
- Open-ended speaking prompts
- Dotted underline vocab words in model answers

## Lesson Structure (per slide)
1. Title/Introduction (with cover image)
2. Vocabulary section (10-12 travel words with clickable definitions)
3. Word ordering exercise (scrambled sentence)
4. Open-ended speaking question with model answer

## 12 Lessons

| Lesson | Topic | Key Vocabulary |
|--------|-------|---------------|
| 1 | Airport & Check-in | check-in, boarding pass, baggage allowance, flight delay, gate, carry-on, departure, arrival |
| 2 | Hotel & Accommodation | reservation, reception, amenities, concierge, checkout, housekeeping, room service, front desk |
| 3 | Transportation | taxi, subway, bus stop, timetable, ticket office, platform, fare, transfer |
| 4 | Restaurants & Cafes | reservation, menu, bill, tip, waiter, appetizer, dessert, cuisine |
| 5 | Shopping & Money | exchange rate, credit card, receipt, discount, fitting room, return policy, price tag |
| 6 | Asking Directions | landmark, intersection, map, compass, turn left/right, straight ahead, nearby |
| 7 | Emergencies | lost passport, medical emergency, police station, embassy, helpline, insurance claim |
| 8 | Beach & Leisure | sunblock, parasol, lifeguard, tide, shore, beach volleyball, rental charges |
| 9 | Cultural Sites | museum, gallery, guided tour, entrance fee, audio guide, UNESCO, masterpiece |
| 10 | Weather & Seasons | forecast, precipitation, rainfall, sunny intervals, mild climate, thunderstorm, drizzle |
| 11 | Travel Planning | itinerary, travel insurance, visa requirement, departure time, layover, confirmation email |
| 12 | Common Expressions | excuse me, how much, I'd like, could you please, thank you, you're welcome |

## Technical Implementation

### Theme System (8 themes)
- Theme toggle button on slide 1 only (cycles through 8 palettes)
- Themes: Classic (gold/cyan), Forest (green), Violet (purple), Gold (amber), Crimson (rose), Ocean (blue), Midnight (indigo), Sand (warm)

### Vocabulary Click System
- Dotted underline on B2/C1 words
- Click shows tooltip with definition
- Italian translations in tooltip

### Word Ordering Exercise
- Scrambled words shown as `[word1 / word2 / word3]`
- Click "Reveal Answer" button
- Model answer appears below

### Background Images (Unsplash)
- Cover: `photo-1507525428034-b723cf961d3e` (beach/travel)
- Topics with CSS texture (per user preference for non-relevant images)

## Verification
- 13 slides total
- All vocab words clickable
- Word ordering exercises work
- Speaking prompts include model answers
- `node --check` passes