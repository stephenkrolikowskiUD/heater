# 🔥 HEATER — NBA Streak Prediction Game

A prototype game concept for daily fantasy sports platforms where users predict whether a player's hot streak will continue or end tonight.

## 🎮 Concept

Instead of picking static over/under lines, **Heater** identifies players on active stat streaks and lets users bet on momentum:

- **🔥 Keeps Rolling** — you think the streak continues tonight
- **❄️ Streak Ends** — you think tonight's the cold game

Longer streaks = higher multipliers. A 3-game streak pays 1.4x. An 8-game streak pays 3.5x.

## 📊 Heat Levels

| Streak | Level | Multiplier |
|--------|-------|------------|
| 3 games | ♨️ Warm | 1.4x |
| 4-5 games | 🔥 Heating Up | 1.8x - 2.2x |
| 6-7 games | 🔥🔥 On Fire | 2.8x |
| 8+ games | 🔥🔥🔥 Inferno | 3.5x |

## 🧠 Research Tools Built In

Each streak card includes:
- **Mini bar chart** — visual game-by-game performance vs threshold
- **Matchup context** — opponent Defensive Rating, Pace, and Vegas line
- **AI rationale** — why this streak matters tonight
- **Streak vs Season avg** — is the player truly hot or just meeting baseline?

## 🛠 Tech Stack

- **Frontend:** HTML / CSS / JavaScript (vanilla, no framework)
- **Data Pipeline:** Python (Google Colab) → Google Sheets → Live fetch
- **Data Sources:** NBA API, Odds API (DraftKings props), Gemini AI
- **Hosting:** GitHub Pages

## 🔗 Related Projects

- [NBA DFS Dashboard](https://stephenkrolikowskiUD.github.io/nba-dfs-dashboard) — Full research dashboard with player props, correlations, and AI picks
- Pipeline processes 300+ players, 370+ DK props, and 14 AI-ranked picks daily

## 📋 Features

- [x] Streak detection and heat level classification
- [x] Multiplier scaling based on streak length
- [x] Slip builder with combined payout calculation
- [x] Matchup details (Def Rating, Pace, Line)
- [x] Filter by prop type (PTS, PRA, REB)
- [x] Sort by streak length, payout, or weak defense
- [ ] Live data from Google Sheets API
- [ ] Historical streak tracking and hit rate
- [ ] Streak insurance (partial refund on 0.5 misses)

## 🚀 Live Demo

[Play Heater](https://stephenkrolikowskiUD.github.io/heater)

---

*Built by Stephen Krolikowski — CS @ Underdog Fantasy*
*Concept designed for portfolio purposes*
