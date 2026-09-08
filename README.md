# Chen-Yi Su

Graduate student at Johns Hopkins University, previously Computer Science and Engineering at HKUST. I like problems where a careful measurement changes the answer: how early can you prune LLM reasoning branches, where in a network should uncertainty live, and when does a randomized approximation actually pay for itself.

Open to machine learning engineering and research roles.

## Featured projects

| Project | What it is | One number |
|---|---|---|
| [rnla-pruning](https://github.com/nathan215/rnla-pruning) | Training-free pruning of Best-of-N reasoning branches using randomized leverage scores of hidden states. DeepSeek-R1-Distill-Qwen-1.5B on MATH-500, exact vs sketched SVD, log-prob and random baselines, unit-tested and CI-checked | Prune 16 → 4 branches within the first 300 tokens and keep Pass@4 at 71.5–74.0 % against a 76.5 % ceiling, for an estimated 3.3–3.6× fewer decoded tokens |
| [cifar10-mc-dropout-ood](https://github.com/nathan215/cifar10-mc-dropout-ood-) | Where should Monte Carlo dropout live in a ResNet? Five dropout placements trained with one recipe and evaluated on CIFAR-10-C for accuracy, Brier score, adaptive calibration error and mutual information | Dropout in all residual blocks: ACE 0.18 at severity 5, against 0.27–0.31 for every other placement, including last-layer-only |
| [FYP](https://github.com/nathan215/FYP) | Drone and LoRa IoT system for locating missing people: RSSI path-loss localization, Nelder-Mead and EKF refinement, MQTT backend, React map with live drone data. HKUST CSE final-year project, 2023–24 | Team of three; I built the localization algorithms and most of the backend |
| [bayesian_final_report](https://github.com/nathan215/bayesian_final_report) | Bayesian AR(1) and GARCH(1,1) volatility models for seven tech stocks with hand-written Gibbs samplers, three prior strengths and hierarchical pooling across tickers | 1,254 trading days, chronological 1,040 / 214 split, multi-horizon interval scoring |
| [OSM-Shortest-Path-Algorithms](https://github.com/nathan215/OSM-Shortest-Path-Algorithms) | Dijkstra, bidirectional Dijkstra and A* implemented from scratch and benchmarked against NetworkX on OpenStreetMap graphs of six Taiwanese cities, plus a Django map app. HKUST UROP, 2023 | 6 cities × 3 scenarios × 100 random pairs |

## Areas

LLM inference efficiency · uncertainty and calibration · Bayesian time series · reinforcement learning and IoT systems

## Tools

PyTorch · Hugging Face Transformers · NumPy / SciPy / pandas · scikit-learn · Django · React / Vite · LaTeX
