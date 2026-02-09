# 🏓 Pong — AI vs AI (Self-Play)

A minimal **Pong game built from scratch** where **both paddles are controlled by reinforcement learning agents**.

No sprites.
No Atari.
Only **basic geometric shapes** and **PPO self-play**.



## What this project shows

* Custom Gymnasium environment (no prebuilt games)
* Two AI agents learning via self-play
* Reward shaping for stable training
* Fast CPU-only convergence



## Tech Stack

Python · Gymnasium · Stable-Baselines3 · PPO · Pygame



## Run

```bash
pip install -r requirements.txt
python train.py
python evaluate.py
```



## Demo

After training, run `evaluate.py` to watch **AI vs AI Pong** in real time.

