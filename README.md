# Fishing Frenzy

A simple, addictive HTML5 fishing game that runs on IIS.

## How to Play

1. **Cast**: Hold SPACE or click and hold to charge your cast power
2. **Release**: Let go to cast your line into the water
3. **Wait**: Watch for the bobber to get a bite
4. **Catch**: When you see "FISH ON!", quickly click or press SPACE to reel in!

## Features

- 13 different fish types with varying rarity
- Upgrade system (Rod, Bait, Line, Lucky Charm)
- Fish collection to track your discoveries
- Level progression with XP rewards
- Auto-save to local storage
- Sound effects using Web Audio API
- Responsive design

## Fish Types

| Fish | Value | Rarity |
|------|-------|--------|
| Sardine | 5 | Common |
| Mackerel | 10 | Common |
| Bass | 20 | Uncommon |
| Salmon | 35 | Uncommon |
| Tuna | 50 | Rare |
| Swordfish | 75 | Rare |
| Octopus | 100 | Epic |
| Shark | 150 | Epic |
| Whale | 250 | Legendary |
| Golden Fish | 500 | Legendary |
| Sea Dragon | 1000 | Legendary |
| Treasure Chest | 200 | Legendary |

## Upgrades

- **Better Rod**: Faster fish attraction
- **Premium Bait**: Attract rarer fish
- **Strong Line**: Catch bigger fish
- **Lucky Charm**: More bonus rewards

## Deploying to IIS

1. Create a new site or application in IIS Manager
2. Point the physical path to this folder
3. Ensure the `web.config` file is in place
4. Browse to your site URL

### IIS Requirements

- IIS 7.0 or later
- Static content feature enabled

## Files

- `index.html` - Main game file (all-in-one HTML/CSS/JS)
- `web.config` - IIS configuration file
- `README.md` - This file

## Browser Support

Works in all modern browsers (Chrome, Firefox, Edge, Safari) that support:
- HTML5 Canvas
- Web Audio API
- Local Storage
