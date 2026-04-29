# Void Dominion TTS Assets

Public Tabletop Simulator asset host for Void Dominion.

This repo intentionally contains import-ready PNG assets only. Working SVGs, data, rules, and scripts live in the private working-files repo.

Use GitHub Pages with:
- Source: Deploy from a branch
- Branch: main
- Folder: /root

## TTS Sheet Settings

| Asset | Path | TTS Width | TTS Height | Number | PNG Size |
|---|---|---:|---:|---:|---:|
| objective_deck | `cards/objective_deck.png` | 7 | 3 | 21 | 4095x2457 |
| objective_card_back | `cards/objective_card_back.png` | 1 | 1 | 1 | 2926x4096 |
| ship_reference | `cards/ship_reference.png` | 1 | 1 | 1 | 4096x2472 |
| dice_reference | `cards/dice_reference.png` | 1 | 1 | 1 | 4096x2867 |
| bonus_icon_reference | `cards/bonus_icon_reference.png` | 1 | 1 | 1 | 4096x2895 |
| system_bonus_cards | `cards/system_bonus_cards.png` | 4 | 2 | 8 | 4096x2868 |

Use `cards/objective_deck.png` as the objective deck face sheet.
Use `cards/objective_card_back.png` as the objective deck back image.
Use `rules/current_game_reference.pdf` as the in-table rules reference.
Use `dice/dice_standard_attack.png`, `dice/dice_spicy_attack.png`, `dice/dice_bombardment.png`, `dice/dice_aggressive_defense.png`, and `dice/dice_retreat.png` as custom D6 texture images.
Use individual token images for utility tokens, ship silhouettes, and player sector flags. Suggested copy counts are listed on the index page.

## Generic TTS Pieces To Make

These prototype components are not hosted files because they can be created directly in Tabletop Simulator:

| Component | Count | TTS Setup | Notes |
|---|---:|---|---|
| Colony cubes | 20 per player | Use physical cubes or TTS built-in cubes | Regular cubes placed on surface slots |
| Outpost cube | 1 per player | Use tall cube or TTS built-in block | Counts as 2 dominion value while occupying 1 slot |
| Action pawns | 6 per player | Use physical pawns or TTS built-in pawns | Five normal action pawns plus room for extra action pawn effect |
| Turn order pawn | 1 per player | Use physical pawn or TTS built-in marker | Tracks turn order |
| VP marker | 1 per player | Use physical marker or TTS built-in marker | For VP track |
| VP track | 1 | Not created | Can be built in TTS or added to a future board |

## TTS Color Hex Reference

| Use | Hex | Notes |
|---|---|---|
| P1 player pieces | `#F4F4EE` | Ships, flags, colony cubes, outpost cube, pawns, VP marker |
| P2 player pieces | `#2F6FEA` | Ships, flags, colony cubes, outpost cube, pawns, VP marker |
| P3 player pieces | `#F2C84B` | Ships, flags, colony cubes, outpost cube, pawns, VP marker |
| Ship body fill | `#253147` | Dark ship silhouette fill used by the token art |
| Standard Attack die | `#C65A3A` | Warm combat die color |
| Spicy Attack die | `#CF4E62` | Warm combat die color |
| Bombardment die | `#D99A35` | Warm combat die color |
| Aggressive Defense die | `#3F83C5` | Cool defense die color |
| Retreat die | `#2FA6A0` | Cool defense die color |
| Green planets | `#63A66F` | Planet/system color |
| Red planets | `#CF5050` | Planet/system color |
| Nexus purple | `#866FC5` | Center planet/system color |
| Moons | `#D8DADF` | Moon surface color |
| Slot/light marks | `#F1E8D0` | Colony slots, pale icon details, and light markings |

Example hosted URL after publishing:

```text
https://YOUR_USERNAME.github.io/void-dominion-tts-assets/cards/objective_deck.png
```
