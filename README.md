### Hi, I'm Nathan 👋

I build LLM agents and pull reasoning models apart to see what is inside. Two questions keep pulling me back: how do you get an agent to do real work inside someone else's system without breaking anything, and how much of a model's thinking can you throw away before the answer changes.

- 🔬 **Right now:** [rnla-pruning](https://github.com/nathan215/rnla-pruning) — 300 tokens into a reasoning trace, can you already tell which branches are worth finishing?
- 🤖 **Most of my building:** agents that touch real systems, which in practice means MCP tools, an approval gate in front of anything destructive, and evals for when the agent is confidently wrong
- 😅 **Fun fact:** an agent once ran `git reset --hard` over my uncommitted work while I was asleep. That is roughly how I got interested in human-in-the-loop approval gates.

### Projects

| Project | What it is | One number |
|---|---|---|
| [rnla-pruning](https://github.com/nathan215/rnla-pruning) | Prune Best-of-N reasoning branches early using leverage scores of their hidden states, no training needed. DeepSeek-R1-Distill-Qwen-1.5B on MATH-500, with unit tests and CI | Keep 4 of 16 branches after 300 tokens: Pass@4 71.5–74 % vs a 76.5 % ceiling |
| [cifar10-mc-dropout-ood](https://github.com/nathan215/cifar10-mc-dropout-ood-) | Where should Monte Carlo dropout go in a ResNet? Five placements compared on CIFAR-10-C for accuracy, calibration and uncertainty | Dropout in every block: ACE 0.18 at severity 5, vs 0.27–0.31 for the rest |
| [FYP](https://github.com/nathan215/FYP) | Drone plus LoRa beacon system for finding missing people, from RSSI localization to a live web map. HKUST final-year project, 2023–24 | Team of three; I built the localization algorithms and most of the backend |
| [bayesian_final_report](https://github.com/nathan215/bayesian_final_report) | Bayesian AR(1) and GARCH(1,1) volatility models for seven tech stocks, with Gibbs samplers written from scratch and hierarchical pooling across tickers | Five years of daily returns, chronological 1,040 / 214 split |
| [OSM-Shortest-Path-Algorithms](https://github.com/nathan215/OSM-Shortest-Path-Algorithms) | Dijkstra, bidirectional Dijkstra and A* written from scratch and raced against NetworkX on real road maps of six Taiwanese cities. HKUST UROP, 2023 | 6 cities × 3 scenarios × 100 routes each |

Finishing an M.S. at Johns Hopkins and looking for agent and ML engineering work. Say hi on [LinkedIn](https://linkedin.com/in/chenyisu02).
