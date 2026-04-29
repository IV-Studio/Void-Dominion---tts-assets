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
| utility_tokens | `tokens/utility_tokens.png` | 5 | 1 | 5 | 4095x819 |
| ship_tokens | `tokens/ship_tokens.png` | 3 | 3 | 9 | 4095x4095 |
| sector_flags | `tokens/sector_flags.png` | 3 | 1 | 3 | 4095x1365 |

Use `cards/objective_deck.png` as the objective deck face sheet.
Use `cards/objective_card_back.png` as the objective deck back image.
Use `rules/current_game_reference.pdf` as the in-table rules reference.
Use `dice/dice_standard_attack.png`, `dice/dice_spicy_attack.png`, `dice/dice_bombardment.png`, `dice/dice_aggressive_defense.png`, and `dice/dice_retreat.png` as custom D6 texture images.
Use token sheets for utility tokens, ship silhouettes, and player sector flags.

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

Example hosted URL after publishing:

```text
https://YOUR_USERNAME.github.io/void-dominion-tts-assets/cards/objective_deck.png
```
