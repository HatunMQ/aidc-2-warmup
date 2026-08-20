# aidc-2-warmup

This is the warmup for the first step in the bootcamp.

## Week 1 Recap

**Team:** Team 2 — Hatun (HatunMQ) & Linda (lindaahmedalzahrani-gif)

What our team learned and built during the first week of the AI Data Center bootcamp:

- **Git & GitHub workflow:** branching, committing, opening pull requests, code review and approvals, resolving a real merge conflict, and setting up branch protection rules on `main`.
- **Docker & Linux basics:** running and entering containers, checking running processes (`ps aux`, `top`), inspecting listening ports (`ss -tlnp`), file permissions, and why containers shouldn't run as root.
- **Building a team server:** a shared Python HTTP server where each member added their own `/username` endpoint through branches and pull requests, tested locally with Docker, and updated live via `git pull` without restarting the server.
- **Registering on an external board:** using a small script to register a teammate (and get registered back) on a shared class-wide leaderboard.
- **Running an LLM on a GPU:** connecting to a T4 GPU on Google Colab, picking a model from Hugging Face that fits the hardware, and loading it with `transformers` to generate answers.
- **Understanding generation parameters:** experimenting with `temperature`, `top_k`, `max_new_tokens`, sampling vs. greedy decoding, and batched vs. sequential inference to see how each affects the model's output and speed.