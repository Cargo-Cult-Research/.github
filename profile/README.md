# Cargo Cult Research

Machine learning research, on one machine: a Mac Studio that does the training,
the evaluation and the serving.

Four projects are open, each with a live demo on
[strawrunway.com](https://strawrunway.com). A demo runs only while the machine
is free.

- **[mlx-rl](https://github.com/Cargo-Cult-Research/mlx-rl)** — GRPO
  reinforcement learning of LoRA adapters on Apple Silicon, with verifiable
  rewards; includes teaching a 35B to say "I don't know" and measuring whether
  it meant it.
  [Demo](https://strawrunway.com/rl): one question, trained model and base
  model side by side.
- **J-lens** — a reimplementation of the Jacobian-lens global-workspace readout
  for a 35B mixture-of-experts model.
  [Demo](https://strawrunway.com/jlens): the workspace band, per token, as the
  model writes.
- **brainbow** — expert routing through 40 layers and 256 experts.
  [Demo](https://strawrunway.com/brainbow): the routing drawn as the tokens
  stream.
- **schema** — a reproduction of the Schema ARC-AGI-3 world-model-as-code
  harness on a local 35B.
  [Demo](https://strawrunway.com/schema): the model writing its own model of an
  unseen game, turn by turn.

Also public: **[pybricks-micropython](https://github.com/Cargo-Cult-Research/pybricks-micropython)**
(fork, branch `mlp-module`) — neural-network inference on a LEGO Technic Hub,
in C on the Cortex-M4F.

The repositories behind J-lens, brainbow and schema are private, as is the rest
of the work here — agentic-coding evaluation, long-horizon agent behaviour in
sealed containers, sim-to-real RL. Shared on request.

---

Urs Köster · [strawrunway.com](https://strawrunway.com) ·
[Scholar](https://scholar.google.com/citations?user=duVCaoAAAAAJ)
