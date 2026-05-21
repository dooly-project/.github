# Dooly

### Configuration-agnostic, redundancy-aware profiling for LLM inference simulation. ###

DoolyProf extracts all operations present in an LLM inference forward pass and efficiently profiles only those absent from its latency database. The resulting latency models can be used in downstream LLM inference tasks such as simulation (e.g., DoolySim, [Vidur](https://github.com/microsoft/vidur)) or in latency-prediction-based schedulers (e.g., [llm-d](https://llm-d.ai/blog/predicted-latency-based-scheduling-for-llms)).

📄 **Paper:** [Dooly: Configuration-Agnostic, Redundancy-Aware Profiling for LLM Inference Simulation](https://arxiv.org/abs/2605.07985)

## Repositories

- [**⏱️ DoolyProf**](https://github.com/dooly-project/doolyprof) — The profiler. Performs a single tainted inference pass and selectively profiles operations absent from the latency database.
- [**📊 DoolySim**](#) — Reference simulator built on top of DoolyProf's latency database.

## Installation

Refer to indivudal repositories for installation instructions. 

## Citation
```
@misc{kim2026doolyconfigurationagnosticredundancyawareprofiling,
      title={Dooly: Configuration-Agnostic, Redundancy-Aware Profiling for LLM Inference Simulation}, 
      author={Joon Ha Kim and Geon-Woo Kim and Anoop Rachakonda and Daehyeok Kim},
      year={2026},
      eprint={2605.07985},
      archivePrefix={arXiv},
      primaryClass={cs.DC},
      url={https://arxiv.org/abs/2605.07985}, 
}
```

## License

See individual repositories for license information.
