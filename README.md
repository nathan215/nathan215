### Hi, I'm Chen-Yi 👋

I'm a grad student at Johns Hopkins working on machine learning, mostly on making LLM inference cheaper and getting models to say how sure they are. Before this I studied Computer Science and Engineering at HKUST.

- 🔬 Right now: pruning reasoning branches early in Best-of-N decoding, see [rnla-pruning](https://github.com/nathan215/rnla-pruning)
- 🧰 Daily tools: PyTorch, Hugging Face Transformers, NumPy / SciPy / pandas, React and Django when a project needs a UI
- 💼 Open to machine learning engineering and research roles

### Projects

| Project | What it is | One number |
|---|---|---|
| [rnla-pruning](https://github.com/nathan215/rnla-pruning) | Prune Best-of-N reasoning branches early using leverage scores of their hidden states, no training needed. DeepSeek-R1-Distill-Qwen-1.5B on MATH-500, with unit tests and CI | Keep 4 of 16 branches after 300 tokens: Pass@4 71.5–74 % vs a 76.5 % ceiling |
| [cifar10-mc-dropout-ood](https://github.com/nathan215/cifar10-mc-dropout-ood-) | Where should Monte Carlo dropout go in a ResNet? Five placements compared on CIFAR-10-C for accuracy, calibration and uncertainty | Dropout in every block: ACE 0.18 at severity 5, vs 0.27–0.31 for the rest |
| [FYP](https://github.com/nathan215/FYP) | Drone plus LoRa beacon system for finding missing people, from RSSI localization to a live web map. HKUST final-year project, 2023–24 | Team of three; I built the localization algorithms and most of the backend |
| [bayesian_final_report](https://github.com/nathan215/bayesian_final_report) | Bayesian AR(1) and GARCH(1,1) volatility models for seven tech stocks, with Gibbs samplers written from scratch and hierarchical pooling across tickers | Five years of daily returns, chronological 1,040 / 214 split |
| [OSM-Shortest-Path-Algorithms](https://github.com/nathan215/OSM-Shortest-Path-Algorithms) | Dijkstra, bidirectional Dijkstra and A* written from scratch and raced against NetworkX on real road maps of six Taiwanese cities. HKUST UROP, 2023 | 6 cities × 3 scenarios × 100 routes each |
