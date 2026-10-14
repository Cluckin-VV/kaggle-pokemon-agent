# Pokémon TCG AI Battle — Agent Evaluation Case Study

This repository documents my evaluation process for Kaggle's [Pokémon TCG AI Battle](https://www.kaggle.com/competitions/pokemon-tcg-ai-battle). It intentionally contains **no official game engine, card data, competition assets or restricted source code**.

## What I worked on

- iterated decision policies for a live turn-based game agent;
- inspected replays to separate illegal actions, tactical mistakes and long-horizon planning errors;
- used deterministic seeds and repeated local matches where the competition package allowed it;
- tracked submission versions and treated leaderboard score as a noisy measurement.

## Verified result

The best observed submission scored **919.9** on the public leaderboard. Repeated submissions of the same package produced materially different scores, including lower results, so I do not present 919.9 as a stable policy value or claim a final rank.

## Evaluation lesson

A single leaderboard result was insufficient evidence. My decision log therefore separated:

1. code/package identity;
2. local seeded evidence;
3. replay-level failure categories;
4. repeated remote scores;
5. changes that improved behavior for an understood reason.

## Publication boundary

The competition engine is licensed for competition use and is not redistributed here. This case study publishes only my high-level methodology and verified submission history.

Kaggle profile: [cluckinvv](https://www.kaggle.com/cluckinvv)

