# Awesome Pokémon Papers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of research papers on AI agents that play Pokémon — battling, speedrunning, and beyond.

## Contents

- [Papers](#papers)
  - [Competitive Battling](#competitive-battling)
  - [Game Playing & Speedrunning](#game-playing--speedrunning)
  - [Benchmarks & Competitions](#benchmarks--competitions)
- [Leaderboards](#leaderboards)
  - [Pokemon Battling Leaderboard](#pokemon-battling-leaderboard)
  - [Pokemon Emerald Speedrun Leaderboard](#pokemon-emerald-speedrun-leaderboard)
- [Submit Your Paper](#submit-your-paper)

---

## Papers

### Competitive Battling

- **PokéChamp: An Expert-Level Minimax Language Agent** — Karten, Nguyen, Jin (Princeton, 2025). Minimax tree search powered by LLMs for action sampling, opponent modeling, and value estimation. ICML 2025 Spotlight.
  [[Paper]](https://arxiv.org/abs/2503.04094) [[GitHub]](https://github.com/sethkarten/pokechamp)

- **Metamon: Human-Level Competitive Pokémon via Scalable Offline RL with Transformers** — Grigsby, Xie, Sasek, Zheng, Zhu (UT Austin, 2025). Offline RL using transformer sequence models trained on reconstructed first-person battle logs. Achieves top 10% ranking among active human players without explicit search. RLC 2025.
  [[Paper]](https://arxiv.org/abs/2504.04395) [[GitHub]](https://github.com/UT-Austin-RPL/metamon)

- **PokéLLMon: A Human-Parity Agent for Pokémon Battles with Large Language Models** — Hu, Huang, Liu (2024). LLM agent for Pokemon battling with self-consistency prompting.
  [[Paper]](https://arxiv.org/abs/2402.01118) [[Website]](https://poke-llm-on.github.io/)

- **VGC-Bench: Towards Mastering Diverse Team Strategies in Competitive Pokémon** — Angliss, Cui, Hu, Rahman, Stone (UT Austin, 2025). Benchmark for Pokémon VGC evaluating AI generalization across ~10^139 possible team configurations, with 700K+ battle logs. AAMAS 2026.
  [[Paper]](https://arxiv.org/abs/2506.10326) [[GitHub]](https://github.com/cameronangliss/VGC-Bench)


### Game Playing & Speedrunning

- **Pokémon Red via Reinforcement Learning** — Pleines, Addis, Rubinstein, Zimmer, Preuss, Whidden (2025). Deep RL baseline agent that completes an initial segment of Pokémon Red up to Cerulean City, addressing challenges of open-world RPGs as RL testbeds.
  [[Paper]](https://arxiv.org/abs/2502.19920) [[GitHub]](https://github.com/PWhiddy/PokemonRedExperiments)

### Benchmarks & Competitions

- **The PokéAgent Challenge: Competitive and Long-Context Learning at Scale** — Karten, Grigsby, Milani, Vodrahalli, Zhang, Fang, Zhu, Jin (2025). NeurIPS 2025 competition with two tracks: competitive battling and RPG speedrunning. Features access to 3.5M+ battle dataset for advancing AI decision-making and long-horizon planning.
  [[Paper]](https://sethkarten.ai/data/NeurIPS_2025_PokeAgent_Challenge.pdf) [[Website]](https://pokeagent.github.io/)

---

## Leaderboards

### Pokemon Battling Leaderboard

Official AI-only battling rankings.

**[View Live Battling Leaderboard](https://battling.pokeagentchallenge.com/ladder)**

### Pokemon Emerald Speedrun Leaderboard

Ranked by agent progress through Pokémon Emerald. Milestones:

1. Game Start
2. Littleroot Town
3. Starter Pokémon
4. Rival Battle
5. Petalburg City
6. Route to Rustboro
7. First Gym

| Rank | Team | Progress | Runtime |
|------|------|----------|---------|
| — | *No entries yet* | — | — |

---

## Submit Your Paper

We welcome submissions from the research community! To add your paper:

1. **Fork** this repository.
2. **Add your paper** to the appropriate section in `README.md` following the existing format.
3. **Submit a pull request** with a link to your paper (arXiv, conference proceedings, etc.).

### Leaderboard Submission

To appear on a leaderboard, include the following in your PR:

- **Battling leaderboard**: Submit your head-to-head battle logs.
- **Speedrun leaderboard**: Submit a video recording of your agent completing Pokémon Emerald.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

## License

[![CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
