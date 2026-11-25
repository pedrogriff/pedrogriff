# Pedro Griff Marcincowski

I work in compensation and I build AI agents that prepare comp analysis. Models write the words. Code computes the money. People decide.

**Now.** I just wrapped up [comp-insight-advisor](https://github.com/pedrogriff/comp-insight-advisor), my capstone for Carnegie Mellon's 2026 executive education program in agentic AI. It reads a synthetic company's pay, equity and offer data and drafts a retention brief. A comp partner reviews it and decides what goes to a VP. All seven build logs are on [LinkedIn](https://www.linkedin.com/in/pedrogriff/), ending with [Build log 7/7. Demo and scorecard](https://www.linkedin.com/feed/update/urn:li:activity:7531228842783408128/).

## Projects

| Project | What it does | What backs it |
| :--- | :--- | :--- |
| [comp-insight-advisor](https://github.com/pedrogriff/comp-insight-advisor) | Guarded five-node LangGraph squad that drafts retention and policy briefs for a comp partner to review. SQL and Python compute every number. The model writes the summary paragraph, held to the facts. | 238 tests, 158 of 163 seeded faults rejected, a [scorecard](https://github.com/pedrogriff/comp-insight-advisor/blob/main/experiments/final_evaluation/scorecard.md), the [final report](https://github.com/pedrogriff/comp-insight-advisor/blob/main/checkpoints/checkpoint_7_1.md) and a [demo video](https://youtu.be/YprdRwfI1LU) |
| [vesting-sim-engine](https://github.com/pedrogriff/vesting-sim-engine) | Vesting schedules whose monthly tranches always add up to the grant, plus Monte Carlo valuation | A property-based test that runs 200 random grants of up to 10 million shares |

## Infrastructure

- [homelab-k8s-talos](https://github.com/pedrogriff/homelab-k8s-talos). The bare-metal Kubernetes cluster my projects run on. Talos Linux on Proxmox, Cilium eBPF, Argo CD for deploys, Prometheus and Grafana for metrics. It runs a merit and offer workflow service, a compensation MCP service and Ollama with pgvector.

## Lab

- [algocore-ds](https://github.com/pedrogriff/algocore-ds). Data structures from scratch, with benchmarks.
- [libft](https://github.com/pedrogriff/libft) and [42sp-Basecamp](https://github.com/pedrogriff/42sp-Basecamp). C from 42 São Paulo in 2021, including my first library.

## Elsewhere

- [playgriff.me](https://www.playgriff.me/) for live demos
- [LinkedIn](https://www.linkedin.com/in/pedrogriff/) for the build log

Personal projects on synthetic data. Views are my own.
